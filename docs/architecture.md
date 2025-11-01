## Arquitetura

Cliente (JavaFX/Android) ↔ Firebase (Auth + Firestore)

```mermaid
flowchart TB
A[Usuário] --> B[Interface]
B --> C[SQLite]
C --> D[Firestore]
B --> E[Exporter PDF/CSV]
```