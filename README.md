# Portafolio de proyectos de datos, automatización e IA aplicada

Luis Chavarria Cayul — Ingeniero Civil Industrial, planificación y optimización de operaciones de
transporte público.

Estos proyectos nacen de un mismo interés: usar datos, automatización y modelos de lenguaje para
resolver problemas concretos de operación. Son desarrollos propios, hechos de forma autodidacta, y
en todos el criterio de ingeniería está puesto en la validación: los números se contrastan, se
verifican contra una segunda fuente cuando es posible, y el resultado se puede reproducir.

## Proyectos

| Proyecto | Qué es | Stack |
|---|---|---|
| [Simulador operacional de flota eléctrica](02_simulador-flota-electrica) | Simulación de la operación diaria de una flota de buses eléctricos: autonomía, estado de carga, ventanas de recarga y verificación de la jornada siguiente | Python, Streamlit, Plotly, pandas |
| [Dashboard operacional y económico](01_dashboard-operacional-powerbi) | Modelo analítico y tablero para el seguimiento de la programación de una unidad de transporte: kilómetros, flota, ingresos e indicadores de calidad | Power BI (.pbip), DAX, Power Query, Python |
| [Agente de postulaciones laborales](03_agente-postulaciones-llm) | Agente que extrae ofertas de LinkedIn, las evalúa contra un currículum con un modelo de lenguaje y prioriza las postulaciones | Python, Streamlit, SQLite, Playwright, LLM |
| [Pipeline de OCR y traducción](04_pipeline-traduccion-ocr) | Sistema web para convertir PDF a Markdown y traducir documentos y manga conservando la estructura, con procesamiento local | Python, FastAPI, PyMuPDF, CTranslate2, LLM local |

## Demostraciones en línea

Se pueden explorar en el navegador, sin instalar nada y con datos sintéticos:

- **Simulador de flota eléctrica**: https://luisalbertochavarria.github.io/simulador-flota-electrica/
- **Tablero operacional y económico**: https://luisalbertochavarria.github.io/dashboard-operacional-powerbi/

## Enfoque común

- **Validación antes que resultado**: los números se cruzan contra una fuente independiente y se
  documentan los criterios y topes aplicados.
- **Procesamiento local cuando importa la privacidad**: los modelos de lenguaje y de traducción
  pueden correr de forma totalmente local.
- **Datos sintéticos en lo que no se puede publicar**: los proyectos que trabajan con información
  contractual o de terceros se publican con datos ficticios generados, para que cualquiera pueda
  ejecutarlos sin exponer información sensible.

## Sobre los datos

Ninguno de estos repositorios incluye datos operacionales, contractuales ni de terceros. Cuando un
proyecto requiere datos para funcionar, estos se generan de forma sintética y el generador está
incluido en el propio repositorio.

## Licencia

MIT. Ver el archivo `LICENSE` de cada repositorio.
