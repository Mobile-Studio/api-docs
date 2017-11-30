---
title: "AddPhoneForAccount"
description: "AddPhoneForAccount"
weight: 8
---

#### Tipo POST – Nombre: AddPhoneForAccount ####

Descripción: Crea el telefono de la cuenta actual

URL: `https://api-sso.azurewebsites.net:443/Accounts/Me/Phone`

Parámetros de Entrada:

* phone --> Se debe establecer el teléfono de acuerdo al siguiente JSON

```json
{
  "countryCode": 0,
  "areaCode": 0,
  "number": 0,
  "updatedAt": "2017-10-02T13:31:25.980Z"
}
```

Response:

