---
title: "CreateNewAddressForAccount"
description: "CreateNewAddressForAccount"
weight: 2
---

#### Tipo POST – Nombre: CreateNewAddressForAccount ####

Descripción: Crea una nueva direccion a una cuenta específica

URL: `https://api-sso.azurewebsites.net:443/Accounts/{account}/Addresses`

Parámetros de Entrada:

* account --> Se debe ingresar el token de la cuenta
* address --> Se debe ingresar  la dirección en formato JSON

```json
{
  "address": "string",
  "number": "string",
  "houseOrDepto": "string",
  "type": "string",
  "phones": [
    {
      "countryCode": 0,
      "areaCode": 0,
      "number": 0
    }
  ],
  "locations": [
    {
      "id": 0,
      "name": "string",
      "type": 0,
      "parent": 0
    }
  ],
  "country": "string"
}
```

Response: