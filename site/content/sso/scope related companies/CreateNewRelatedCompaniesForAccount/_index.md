---
title: "CreateNewRelatedCompaniesForAccount"
description: "CreateNewRelatedCompaniesForAccount"
weight: 4
---
#### Tipo POST – Nombre: CreateNewRelatedCompaniesForAccount ####

Descripción: Crea una nueva empresa relacionada para la cuenta actual

URL: `https://api-sso.azurewebsites.net:443/Accounts/Me/Companies`

Parámetros de Entrada:

* company --> Se debe ingresa los datos de la compañia formateados en JSON

```json
{
  "nationalId": "string",
  "businessName": "string",
  "nationalIdType": {
    "name": "string",
    "country": "string"
  }
}
```

Response:
