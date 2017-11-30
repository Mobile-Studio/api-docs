---
title: "CreateNewAddressForAccount_0"
description: "CreateNewAddressForAccount_0"
weight: 4
---

#### Tipo POST – Nombre: CreateNewAddressForAccount_0 ####

Descripción: Crea una nueva direccion a la cuenta actual

URL: `https://api-sso.azurewebsites.net:443/Accounts/{account}/Addresses`

Parámetros de Entrada:

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