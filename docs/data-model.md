## Modelo de Dados

| Entidade | Campos |
|---|---|
| User | userId, email, role |
| ConfigEntry | id, userId, type, payload |
| AuditLog | id, configEntryId, action, timestamp |