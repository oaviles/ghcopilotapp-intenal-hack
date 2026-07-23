# GitHub Copilot App Mini-Hackathon

Bienvenido al Mini-Hackathon de **GitHub Copilot App**. Este evento está diseñado para experimentar de primera mano la potencia de la aplicación de escritorio de GitHub Copilot (basada en Copilot CLI), explorando capacidades como sesiones paralelas de agentes, guía con instrucciones personalizadas, integración con servidores MCP (Model Context Protocol) y la automatización de la integración mediante Agent Merge.

---

## Challenge 1: Configuración del Entorno e Instalación de GitHub Copilot App

* **Title**: Instalación, Conexión y Exploración del Workspace
* **Challenge Description**: 
  Configura tu entorno local clonando el repositorio de pruebas de Tailspin Toys e instalando la aplicación de escritorio de GitHub Copilot. Conecta tu repositorio al workspace de la aplicación para habilitar la interacción con agentes, revisar el backlog inicial y estar listo para la ejecución de tareas.
* **Challenge Scenario**: 
  Eres un desarrollador que se une al equipo de desarrollo del e-commerce Tailspin Toys. El equipo acaba de adoptar la nueva **GitHub Copilot App** para acelerar la entrega de software mediante desarrollo guiado por agentes. Tu primera misión es preparar tu workspace local, enlazar el proyecto y realizar un recorrido por la interfaz de la aplicación para comprender la estructura de las sesiones y la gestión de issues/PRs integrados.
* **Suggested time to solve**: 20 minutos
* **Resources**:
  * [Prerequisites - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/0-prerequisites/)
  * [Install the Copilot App - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/1-install-copilot-app/)
  * [GitHub Copilot App Overview Documentation](https://docs.github.com/copilot/concepts/agents/github-copilot-app)

---

## Challenge 2: Tu Primera Sesión de Agente y Cambio Rápido

* **Title**: Implementación de Rating por Estrellas y Primer Pull Request
* **Challenge Description**: 
  Inicia una sesión de agente autónomo dentro de GitHub Copilot App para solicitar la adición de una funcionalidad de evaluación con estrellas (star rating) en los componentes de productos del proyecto Tailspin Toys. Permite que el agente genere los cambios de código necesarios y envía tu primer Pull Request directamente desde la app.
* **Challenge Scenario**: 
  El equipo de producto ha solicitado incluir una representación visual de calificaciones por estrellas en la lista de productos de la tienda. En lugar de escribir el componente desde cero, utilizarás una sesión de agente en GitHub Copilot App para delegar la implementación, revisar las modificaciones propuestas en el diff integrado de la app y publicar la Pull Request correspondiente.
* **Suggested time to solve**: 20 minutos
* **Resources**:
  * [Running your first agent session - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/2-add-star-rating/)
  * [GitHub Copilot App Documentation](https://docs.github.com/copilot/concepts/agents/github-copilot-app)

---

## Challenge 3: Guía del Agente con Custom Instructions

* **Title**: Estandarización de Documentación mediante Instrucciones Personalizadas
* **Challenge Description**: 
  Aplica un estándar de documentación y código en el proyecto mediante el uso de instrucciones personalizadas (`.github/copilot-instructions.md` o configuración de instrucciones de repositorio). Configura al agente para que siga estas reglas al resolver un issue del backlog y valida que las respuestas y el código generado se apeguen estrictamente al estándar definido.
* **Challenge Scenario**: 
  El arquitecto de software del equipo ha definido nuevas normas organizacionales para la documentación y estilo del código en TypeScript/React. Para evitar revisiones manuales repetitivas, debes instruir a Copilot sobre estas reglas mediante un archivo de *Custom Instructions*, de modo que cualquier tarea futura realizada por el agente respete de forma automática las directrices del proyecto.
* **Suggested time to solve**: 25 minutos
* **Resources**:
  * [Guiding Copilot with custom instructions - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/3-custom-instructions/)
  * [Adding custom instructions for GitHub Copilot](https://docs.github.com/copilot/customizing-copilot/adding-custom-instructions-for-github-copilot)

---

## Challenge 4: Desarrollo de Feature Completa y Validación con MCP Playwright

* **Title**: Desarrollo Autónomo de Filtrado de Productos y Testing con MCP
* **Challenge Description**: 
  Utiliza el modo Autopilot/Plan dentro de la app para construir un sistema completo de filtrado de productos. Posteriormente, conecta el servidor MCP (Model Context Protocol) de Playwright a la aplicación para permitir que el agente explore la interfaz en un navegador real y ejecute pruebas end-to-end de verificación sobre la nueva funcionalidad.
* **Challenge Scenario**: 
  Los usuarios de Tailspin Toys necesitan filtrar los juguetes por categoría y rango de precio. Esta es una funcionalidad de múltiples componentes. Usarás las capacidades de planificación de GitHub Copilot App para desglosar y desarrollar el filtro de forma transparente. Una vez implementado, aprovecharás el servidor MCP de Playwright integrado en la app para que el propio agente abra el navegador, interactúe con la app web y certifique que el filtro funciona correctamente.
* **Suggested time to solve**: 30 minutos
* **Resources**:
  * [Building a feature with Autopilot - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/4-build-filtering/)
  * [Testing with Playwright MCP - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/5-mcp-playwright/)
  * [GitHub Copilot & Model Context Protocol (MCP)](https://docs.github.com/copilot/concepts/agents/github-copilot-app)

---

## Challenge 5: Automatización de Integración con Agent Merge y Lienzos de Trabajo

* **Title**: Integración Continua con Agent Merge y Planificación en Canvases
* **Challenge Description**: 
  Aprovecha la funcionalidad **Agent Merge** de GitHub Copilot App para solucionar conflictos, ejecutar rebase, resolver fallas en el pipeline de CI y fusionar el Pull Request de filtrado sin intervención manual compleja. Finalmente, crea un Canvas compartido para mapear los siguientes pasos y tareas recurrentes del proyecto.
* **Challenge Scenario**: 
  Tu PR de filtrado tiene conflictos con la rama principal y requiere ajustes en las pruebas de integración tras los últimos cambios del equipo. En lugar de resolver el rebase y corregir los tests manualmente, encargas a **Agent Merge** la gestión del PR. Observa cómo el agente navega el proceso de revisión, corrige el CI y realiza el merge. Para finalizar, organizas la planificación de la iteración creando un Canvas interactivo dentro del workspace.
* **Suggested time to solve**: 25 minutos
* **Resources**:
  * [Merging with Agent Merge - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/6-agent-merge/)
  * [Planning with canvases - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/7-canvases/)
  * [GitHub Copilot App Review & Next Steps](https://github-samples.github.io/copilot-workshops/app/8-review/)
