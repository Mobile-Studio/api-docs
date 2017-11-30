---
title: "Portal de Desarrolladores Movilidad Sodimac"
description: "Open Portal"
---

# Portal de Desarrolladores Movilidad Sodimac

En este portal encontrarás toda la información que necesitas para consumir los servicios disponibles de Movilidad Sodimac.

### Explora nuestro catálogo en crecimiento de APIs

1. [SSO]({{%relref "sso/_index.md" %}})
1. [Checkout]({{%relref "checkout/_index.md" %}})
1. [Catalogo Regional de Productos]({{%relref "car/_index.md" %}})




{{<mermaid align="left">}}
graph LR;
    A[Legados Sodimac] -->|MDW| B(Azure)
    B[Nube] -->|MDW| A
    B --> C{Microservicios}
    C --> D[SSO]
    C --> E[Checkout]
    C --> F[Car]
    C --> G[Proyectos]
    C --> H[Pechera]
{{< /mermaid >}}


