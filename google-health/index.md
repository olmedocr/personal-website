---
layout: health-info
title: Asistente personal para Google Health
description: Integración personal de solo lectura para consultar datos de Google Health en ChatGPT.
permalink: /google-health/
---

Esta integración de Raul Olmedo permite consultar y analizar sus propios datos de Google Health procedentes de Fitbit desde ChatGPT. Es un proyecto personal, sin registro público ni servicio comercial. En la autorización de Google puede aparecer con el nombre **ChatGPT Google Health Plugin**.

## Qué hace

Con el consentimiento de su titular, consulta perfil, ajustes, actividad y fitness, métricas de salud, sueño, nutrición, electrocardiogramas (ECG) y notificaciones de ritmo irregular. La disponibilidad depende de los datos registrados y del dispositivo. Los permisos sobre Google Health son de **solo lectura**.

## Cómo se usan los datos

El servidor personal se ejecuta en infraestructura doméstica y se conecta a ChatGPT mediante un túnel de OpenAI. Cuando se usa una herramienta, los resultados de la consulta pueden incluir datos de salud y se envían a OpenAI para responder en ChatGPT. ChatGPT también puede enviar al complemento contexto relevante de la consulta, según sus funciones y ajustes.

Las credenciales de Google se conservan en el servidor personal para renovar el acceso. Esta web publica únicamente información sobre el proyecto: no muestra datos de salud ni permite acceder al servidor.

Lee la [política de privacidad]({{ '/google-health/privacy/' | relative_url }}) y las [condiciones de uso]({{ '/google-health/terms/' | relative_url }}) antes de autorizar o utilizar la integración. El consentimiento de Google se concede en su propia pantalla de autorización y puede revocarse desde la cuenta de Google.

## Uso limitado

La información recibida de Google Health API se utiliza exclusivamente para las funciones descritas, conforme a los requisitos de uso limitado de la [Política para desarrolladores y datos de usuario de Google Health](https://developers.google.com/health/policies/health-api-developer-user-data-policy). Los datos se utilizan para las funciones de consulta y análisis solicitadas; no se venden ni se utilizan para publicidad.

## Contacto

Responsable: **Raul Olmedo**. Para cuestiones técnicas, puedes contactar a través de su [perfil de GitHub](https://github.com/olmedocr). No publiques datos de salud, contraseñas ni tokens en incidencias públicas.
