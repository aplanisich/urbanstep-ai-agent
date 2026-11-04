# UrbanStep – Agente Conversacional de IA

**Automatización inteligente de atención al cliente utilizando n8n, inteligencia artificial e integración de herramientas externas.**

## Descripción del proyecto

UrbanStep es un proyecto integrador desarrollado para simular un agente conversacional de inteligencia artificial para una tienda de zapatillas.

El objetivo es automatizar la atención al cliente, interpretar sus consultas, analizar el contexto de las conversaciones y registrar información relevante para facilitar el seguimiento comercial.

El agente permite procesar mensajes, identificar la intención del cliente y generar respuestas contextualizadas.

## Objetivos

- Automatizar consultas de atención al cliente.
- Interpretar mensajes mediante inteligencia artificial.
- Identificar sentimiento, intención, etapa del proceso de compra y prioridad.
- Registrar conversaciones y datos de clientes.
- Facilitar el seguimiento de oportunidades comerciales.
- Integrar distintas herramientas en un flujo automatizado.

## Tecnologías y herramientas

- **n8n:** diseño y orquestación de workflows y automatizaciones.
- **Google Gemini:** análisis de mensajes mediante inteligencia artificial.
- **Supabase:** almacenamiento y gestión de datos.
- **Telegram:** canal de comunicación con el agente.
- **Zoho CRM:** integración para la gestión de clientes y oportunidades.
- **Gmail:** integración para comunicaciones por correo electrónico.
- **Slack:** integración para notificaciones y comunicación interna.
- **n8n Forms:** recepción de información mediante formularios.

## Arquitectura y funcionamiento

El flujo automatizado conecta los distintos servicios para procesar las consultas de los clientes.

1. El cliente envía un mensaje a través de Telegram.
2. n8n recibe y procesa la información.
3. Gemini analiza el mensaje y devuelve información estructurada.
4. El sistema identifica el sentimiento, la intención, la etapa del proceso de compra y la prioridad.
5. Supabase almacena los registros correspondientes.
6. El flujo permite integrar herramientas de gestión comercial y comunicación.

## Ejemplo de análisis realizado

En una prueba de funcionamiento, el agente procesó una consulta general sobre los modelos de zapatillas disponibles y generó el siguiente análisis:

| Campo | Resultado |
|---|---|
| Sentimiento | Neutral |
| Intención | Consulta de producto |
| Etapa del proceso de compra | Descubrimiento |
| Prioridad | Media |

## Estructura del repositorio

- `UrbanStep_workflow_publico_sanitizado.json`: workflow de n8n preparado para compartir públicamente.

## Cómo utilizar el workflow

1. Descargar el archivo JSON del repositorio.
2. Importarlo en una instancia de n8n.
3. Configurar las credenciales de los servicios correspondientes.
4. Reemplazar los identificadores de ejemplo por los propios.
5. Configurar las conexiones y probar el flujo.

**Importante:** el archivo publicado no contiene credenciales privadas. Para ejecutar el workflow es necesario configurar las credenciales y los identificadores de cada servicio en la propia instancia de n8n.

## Aprendizajes aplicados

Este proyecto permitió integrar conocimientos de:

- Automatización de procesos con n8n.
- Integración de APIs y servicios externos.
- Aplicación de inteligencia artificial a procesos de negocio.
- Procesamiento de información estructurada.
- Diseño de flujos conversacionales.
- Gestión y almacenamiento de datos con Supabase.

---

## Evidencias del proyecto

### Workflow de automatización en n8n
![Workflow](screenshots/workflow-n8n.png)

### Atención conversacional por Telegram
![Telegram](screenshots/telegram.png)

### Formulario web
![Formulario web](screenshots/formulario-web.png)

### Encuesta NPS
![NPS](screenshots/nps.png)

**Proyecto desarrollado como parte de la formación en Automatización con IA.**
