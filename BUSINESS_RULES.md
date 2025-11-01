# 📋 Regras de Negócio – Sistema de Configuração e Auditoria de Rede

## 1. Regras Gerais
1. Todo usuário deve estar autenticado via Firebase antes de acessar as configurações.
2. Configurações de rede são salvas localmente e sincronizadas no Firestore.
3. Relatórios devem conter data, hora e tipo de configuração.
4. Apenas administradores podem excluir registros de auditoria.

## 2. Regras Específicas

### 2.1 IP Fixo
- O sistema valida o formato do IP (IPv4).
- DNS e Gateway são opcionais, mas recomendados.
- Ao aplicar, gera log automático no histórico.

### 2.2 PPPoE
- Requer login e senha válidos.
- As credenciais são armazenadas com criptografia AES.
- Desconexões são registradas automaticamente.

### 2.3 DHCP
- Reativa a configuração automática da interface de rede.
- Gera evento “Restaurar padrão” no log.

### 2.4 Relatórios
- Exportação apenas em PDF e CSV.
- O arquivo é nomeado com timestamp automático.
- Relatórios podem ser filtrados por data, tipo e usuário.

### 2.5 Diagnóstico
- Realiza ping no gateway e DNS primário.
- Exibe latência média e status da conexão.

---

## 3. Regra de Segurança
- Todos os dados sensíveis são criptografados localmente.
- Firebase Authentication garante login seguro via e-mail/senha.
