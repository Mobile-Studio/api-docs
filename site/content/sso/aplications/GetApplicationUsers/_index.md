---
title: "GetApplicationUsers"
description: "GetApplicationUsers"
weight: 4
---

#### Tipo – Nombre: GET - GetApplicationUsers ####

Descripción: Obtiene los usuarios registrados para la aplicación específica

URL: `https://api-sso.azurewebsites.net:443/Applications/Users`

Parámetros de Entrada:

* Opcionales:
  * select --> Fields selector (comma separated)
  * filter --> collection of filter's (comma separated): {field} {operator} {value}
  * orderBy --> Order by clause: {field} (asc|desc)
  * limit --> Limit the number of records returned
  * offset --> Skip records before returning anything

Response:
