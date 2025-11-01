# 🧩 Estrutura e Componentes do Sistema

## 1. Diagrama de Casos de Uso (Resumo)

**Atores:**
- Usuário
- Administrador
- Sistema Android

**Casos de Uso:**
1. Fazer login
2. Configurar IP Fixo
3. Configurar PPPoE
4. Ativar DHCP
5. Gerar Relatórios
6. Diagnosticar Conexão
7. Exportar Histórico

---

## 2. Diagrama de Classes (Resumo)
- **Classe Usuário**: autenticação, permissões.
- **Classe Configuração**: tipo, parâmetros, data.
- **Classe Relatório**: geração, exportação.
- **Classe Diagnóstico**: latência, status.
- **Classe FirebaseService**: sincronização e logs.

---

## 3. Fluxo de Telas
Login → Dashboard → Configurações → Relatórios → Diagnóstico

---

## 4. Estrutura de Dados (Firestore)

```
users/
  uid/
    email
    nome
    role
configurations/
  id/
    type (IP|PPPoE|DHCP)
    dataHora
    parametros
    usuario
reports/
  id/
    tipo
    dataInicio
    dataFim
    arquivo
```
