---
title: "AssignUsersAndRoles"
description: "AssignUsersAndRoles"
weight: 7
---
#### Tipo – Nombre: PATCH - AssignUsersAndRoles ####

Descripción: [BULK] Creación de un usuario y asignación de funciones (con el perfil de usuario básico predeterminado)

URL: `https://api-sso.azurewebsites.net:443/Applications/Users/{country}`

Parámetros de Entrada:

* country --> Se debe ingresar el país
* newAccount --> Se debe ingresar los datos de la cuenta en formato JSON

```json
[
  {
    "email": "string",
    "fullname": "string",
    "password": "string",
    "avatar": "string",
    "nationalId": "string",
    "roles": [
      {
        "identifier": "string"
      }
    ]
  }
]
```

Response:
