---
title: "Post"
description: "Post"
weight: 9
---
#### Tipo POST – Nombre: Post ####

Descripción: Registre una Aplicación para habilitar el acceso a los endpoints securitizados (JWT Access)

URL: `https://api-sso.azurewebsites.net:443/Applications`

Parámetros de Entrada:

* application --> Se debe ingresar los datos de la aplicación formateados en JSON

```json
{
  "name": "string",
  "description": "string",
  "avatar": "string",
  "origins": "string",
  "expirationToken": 0,
  "scopes": [
    "string"
  ]
}
```

Response:

