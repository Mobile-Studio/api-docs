---
title: "AssignRolesToUser"
description: "AssignRolesToUser"
weight: 6
---
#### Tipo PUT – Nombre: AssignRolesToUser ####

Descripción: Obtiene los roles registrados para un usuario específico

URL: `https://api-sso.azurewebsites.net:443/Applications/Users/{user}/Roles`

Parámetros de Entrada:

* user --> Se debe ingresar el token de usuario
* roles --> Se debe ingresar los roles a asignar mediante JSON

```json
[
  {
    "token": "string"
  }
]
```

Response: