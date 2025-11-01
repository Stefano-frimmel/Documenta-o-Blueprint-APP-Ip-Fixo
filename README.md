# 📱 Sistema de Configuração e Auditoria de Rede Android

**Projeto Integrador – 4º Bimestre 2025**  
**Curso:** Análise e Desenvolvimento de Sistemas  
**Aluno:** Stéfano Barion Frimmel – RA: 163755-23  
**Instituição:** UNINGÁ – Centro Universitário  
**Cidade:** Maringá/2025  

---

## 🧠 1. Visão Geral

O projeto evoluiu a partir da versão anterior (JavaFX Desktop) e agora apresenta:
- **Nova interface em Android Studio (SDK + Java/Kotlin);**
- **Autenticação com Firebase Authentication;**
- **Dashboard de conexões e relatórios com gráficos interativos;**
- **Nova tela de Configuração Avançada de Rede.**

O sistema continua com o propósito de **simplificar a configuração de IP Fixo, PPPoE e DHCP**, agora com **monitoramento ativo e relatórios em tempo real**.

---

## ⚙️ 2. Tecnologias Utilizadas

| Categoria | Tecnologias |
|------------|--------------|
| Linguagens | Java e Kotlin |
| IDEs | Android Studio, IntelliJ IDEA |
| Banco de Dados | Firebase Firestore, Realtime Database e SQLite |
| Bibliotecas | Firebase SDK, MPAndroidChart, iTextPDF |
| Plataforma | Android (SDK 31+) |

---

## 🚀 3. Principais Funcionalidades

| Funcionalidade | Descrição |
|----------------|------------|
| 🔐 Login e Registro | Usuário se autentica via Firebase Authentication. |
| 🌐 Configuração IP Fixo | Define IP, Máscara, Gateway e DNS. |
| 🔌 PPPoE Automático | Login e Senha armazenados com criptografia local. |
| ⚡ DHCP Dinâmico | Restauração da configuração automática. |
| 📊 Relatórios Gerenciais | Geração de PDF/CSV e gráficos de uso. |
| 🔔 Notificações | Alerta sobre desconexões ou falhas na configuração. |
| 🧭 Modo Diagnóstico | Verifica a conectividade e latência da rede. |

---

## 📈 4. Evoluções do 4º Bimestre

| Área | Atualização |
|------|--------------|
| Interface | Design Material 3 + modo escuro automático |
| Banco de Dados | Sincronização em tempo real com Firestore |
| Relatórios | Gráficos interativos com MPAndroidChart |
| Segurança | Criptografia AES local de credenciais |
| Desempenho | Redução de 30% no tempo de carregamento de dados |

---

## 🧾 5. Telas do Sistema

1. **Tela de Login / Registro**
2. **Tela Inicial / Dashboard**
3. **Tela IP Fixo**
4. **Tela PPPoE**
5. **Tela DHCP**
6. **Tela de Relatórios**
7. **Tela Configuração Avançada**
8. **Tela Diagnóstico de Rede**

---

## 🧩 6. Regras de Negócio
> (Detalhadas no arquivo `BUSINESS_RULES.md`)

---

## 📅 7. Histórico de Atualizações
> (Ver `CHANGELOG.md`)

---

## 💬 8. Considerações Finais

O sistema evoluiu de um protótipo de configuração local para uma **plataforma móvel completa**, capaz de configurar, auditar e monitorar redes diretamente em dispositivos Android.  
O uso do Firebase garante **portabilidade e segurança**, enquanto os relatórios em tempo real oferecem **transparência e controle** para técnicos e usuários.

---

## 👨‍💻 Autor

**Stéfano Barion Frimmel**  
RA: 163755-23  
📍 UNINGÁ – Centro Universitário  
📅 4º Bimestre / 2025  
