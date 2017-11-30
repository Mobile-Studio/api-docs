---
title: "CreateNewRelatedCompanies"
description: "CreateNewRelatedCompanies"
weight: 2
---

#### Tipo POST – Nombre: CreateNewRelatedCompanies ####

Descripción: Crea una nueva empresa relacionada para una cuenta específica

URL: `https://api-sso.azurewebsites.net:443/Accounts/{account}/Companies`

Parámetros de Entrada:

* account --> Se debe ingresar el token de la cuenta
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