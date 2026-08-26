# Mobiliario Paty — Demostración web

[English](README.md)

Concepto de sitio comercial responsive para **Mobiliario Paty**, negocio de renta de mobiliario, carpas y equipo para eventos en Saltillo y municipios cercanos.

La demostración presenta los servicios de manera más clara y ayuda a que cada prospecto prepare una solicitud ordenada antes de continuar la conversación por WhatsApp.

## Demostración publicada

**[Ver el sitio](https://resilient-madeleine-0dbb7b.netlify.app)**

## Funciones principales

- Diseño responsive para celular, tableta y computadora
- Presentación de servicios e inventario para diferentes tipos de evento
- Planeador interactivo con fecha, ubicación, invitados y selección de servicios
- Generación de una consulta estructurada para continuar por WhatsApp
- Galería fotográfica y explicación del proceso de contratación
- Navegación móvil y botón permanente de contacto por WhatsApp
- HTML semántico, indicadores de enfoque, enlace para saltar al contenido y compatibilidad con movimiento reducido
- Metadatos Open Graph y descripción básica para buscadores
- Sin frameworks, administrador de paquetes, proceso de compilación ni dependencias externas de JavaScript

## Tecnologías

- HTML5
- CSS3
- JavaScript puro
- Netlify para el despliegue

## Estructura del proyecto

```text
mobiliario-paty-demo/
├── assets/
│   ├── carpa-evento.jpg
│   ├── carpa-grande.jpg
│   ├── hero-evento.jpg
│   └── montaje-mesas.jpg
├── index.html
├── README.md
└── README.es.md
```

## Ejecución local

No requiere instalación. Clona el repositorio y abre `index.html` en el navegador:

```bash
git clone https://github.com/josecontactdev-cloud/mobiliario-paty-demo.git
cd mobiliario-paty-demo
```

También puedes levantar un servidor local con Python:

```bash
python -m http.server 8000
```

Después abre `http://localhost:8000`.

## Funcionamiento de la consulta por WhatsApp

1. El visitante indica su nombre, tipo de evento, fecha, ubicación y cantidad aproximada de invitados.
2. Selecciona los servicios que le interesan y puede agregar detalles adicionales.
3. El sitio prepara un mensaje estructurado y abre WhatsApp.
4. El visitante revisa el mensaje antes de decidir si lo envía.

La demostración no calcula precios, confirma disponibilidad, envía información automáticamente ni genera una reservación.

## Alcance actual

Este repositorio contiene un concepto de interfaz creado para validar una propuesta comercial. La información, fotografías, servicios, cobertura y textos definitivos deben ser revisados y autorizados por Mobiliario Paty antes de utilizarse en producción.

## Posibles mejoras

- Sustituir el contenido conceptual por la información oficial del negocio
- Agregar un catálogo completo de inventario y paquetes
- Integrar analítica para medir conversiones a consulta
- Añadir datos estructurados y metadatos SEO de producción
- Conectar un gestor de contenido para facilitar actualizaciones
- Incorporar disponibilidad o seguimiento de prospectos si el negocio lo requiere

## Autor

Desarrollado por [José](https://github.com/josecontactdev-cloud).

## Aviso de uso

Esta es una demostración comercial. El repositorio no incluye una licencia de código abierto y su contenido y recursos visuales no deben reutilizarse sin la autorización correspondiente.
