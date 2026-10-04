---
layout: health-info
title: Política de privacidad
description: Acceso, uso, almacenamiento y eliminación de datos en la integración personal para Google Health.
permalink: /google-health/privacy/
---

Última actualización: **4 de octubre de 2026**.

Esta política describe la integración personal de Raul Olmedo, denominada en estas páginas «Asistente personal para Google Health» y en el consentimiento de Google «ChatGPT Google Health Plugin».

## Datos y finalidad

La integración solicita acceso de solo lectura a perfil, ajustes, actividad y fitness, métricas de salud, sueño, nutrición, ECG y notificaciones de ritmo irregular. Consulta los datos disponibles para responder a solicitudes de consulta, resumen y análisis personal en ChatGPT. No modifica los registros de Google Health y no presta un servicio de diagnóstico médico.

También utiliza credenciales OAuth y datos técnicos necesarios para conectar, renovar y diagnosticar el servicio. Las herramientas administrativas de autorización pueden gestionar las credenciales locales.

## Dónde se guardan

El servidor y las credenciales OAuth se alojan en infraestructura doméstica administrada por Raul Olmedo. Las credenciales se conservan en almacenamiento persistente con acceso restringido; los administradores de esa infraestructura pueden acceder a ellas. La caché de consultas del MCP está desactivada en la configuración actual. Esto no elimina los registros originales en Google ni las respuestas guardadas en ChatGPT.

El acceso a Google y la conexión mediante el túnel utilizan conexiones cifradas. Esta política no afirma que los archivos de credenciales estén cifrados en reposo: los permisos de archivo restringen su acceso, pero no equivalen a cifrado.

## Información compartida con terceros

**Google** recibe las solicitudes de autorización y consulta y conserva los datos originales conforme a sus políticas.

**OpenAI** recibe los resultados de las herramientas utilizadas en ChatGPT, que pueden contener datos de salud. El contexto que ChatGPT envíe al complemento puede incluir información relevante de la consulta. El tratamiento y conservación en ChatGPT dependen de las políticas del servicio y de la configuración de la cuenta; consulta la [política de privacidad de OpenAI](https://openai.com/policies/privacy-policy/) y los controles de datos de ChatGPT.

**Netlify** aloja estas páginas y puede procesar información técnica de las visitas, como la dirección IP y los registros de acceso, según su [política de privacidad](https://www.netlify.com/privacy/). **GitHub** aloja el código fuente público de la web. Estas páginas no incorporan formularios de salud, analítica propia ni rastreadores añadidos por esta integración. Las credenciales y los registros de salud no se publican en el repositorio de la web.

## Conservación y eliminación

Las credenciales se conservan mientras se utiliza la integración y hasta que se eliminan del servidor. Para detener el acceso:

1. Revoca la autorización desde las [conexiones de tu cuenta de Google](https://myaccount.google.com/connections).
2. Desconecta el complemento en los ajustes de ChatGPT.
3. Elimina las credenciales persistentes del servidor y las copias de seguridad que las contengan, si existen.

Revocar Google o desconectar el complemento no borra las respuestas ya guardadas en ChatGPT. Su eliminación se gestiona desde ChatGPT. Los datos originales de Google Health se gestionan por separado desde Google. Desconectar un servicio no elimina automáticamente los archivos del servidor doméstico.

## Uso limitado y control

La información recibida de Google Health API se utiliza exclusivamente para las funciones descritas, conforme a los requisitos de uso limitado de la [Política para desarrolladores y datos de usuario de Google Health](https://developers.google.com/health/policies/health-api-developer-user-data-policy). No se venden datos ni se utilizan para publicidad. Los datos se comparten con OpenAI para proporcionar las funciones de consulta y análisis que el titular utiliza con su consentimiento.

## Responsable y contacto

Responsable: **Raul Olmedo**. Contacto técnico a través de su [perfil de GitHub](https://github.com/olmedocr). No incluyas información médica, tokens ni contraseñas en mensajes públicos.
