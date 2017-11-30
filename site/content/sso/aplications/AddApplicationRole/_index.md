---
title: "AddApplicationRole"
description: " AddApplicationRole"
weight: 2
---
#### Tipo PUT - Nombre: AddApplicationRole ####

Descripción: Crea un rol para la aplicación específica (la aplicación se envía en el Token JWT)

URL: `https://api-sso.azurewebsites.net:443/Applications/Roles`

Parámetros de Entrada:

* newRole: Se debe enviar los datos del Rol, según el siguiente JSON

```json
Ejemplo:
{
  "file": "string",
  "description": "string",
  "identifier": "string",
  "name": "string"
}
```

Response: