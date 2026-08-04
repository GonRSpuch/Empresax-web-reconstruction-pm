
## 0. Descargo de Responsabilidad (Disclaimer)

Toda la información y documentación presentada en este repositorio ha sido **completamente anonimizada y modificada (Empresa X)** para proteger la confidencialidad comercial y los acuerdos de confidencialidad (NDA). Los requerimientos, estructuras y entregables no representan la totalidad de la operación real de la empresa y tienen como único fin demostrar la metodología de gestión de proyectos y diseño de producto.

---

## 1. Visión General del Proyecto (Project Overview)

Muchas empresas del sector turismo en España operan con sitios web y plataformas comerciales legacy que han quedado desactualizadas frente a las exigencias actuales del mercado digital. Con el tiempo, esto genera ineficiencias operativas, fricción en la experiencia de usuario (UX) e incapacidad para escalar el canal de ventas B2B con agencias y aliados comerciales.

Este proyecto aborda estos desafíos mediante un **framework integral de Project Management / Product Ownership** para liderar la reestructuración digital de la plataforma. El objetivo es estructurar la estrategia desde la investigación inicial hasta la planificación ágil de la ejecución, alineando los objetivos de negocio con el desarrollo técnico sobre WordPress.

Las soluciones y entregables desarrollados en este proyecto son de alto valor para:
* **Equipos Comerciales y de Ventas:** Al habilitar una arquitectura B2C para cliente final y un canal B2B estructurado para agencias asociadas.
* **Equipos de Desarrollo y UX/UI:** Al contar con un PRD (Documento de Requerimientos de Producto), historias de usuario y una WBS clara que elimina la ambigüedad en la fase de implementación.
* **Dirección y Project Managers:** Al proveer visibilidad total del alcance, plazos y flujo de trabajo a través de un tablero Kanban transparente.

---

## 2. Objetivos del Proyecto (Project Goals)

Este proyecto fue diseñado en torno a tres objetivos estratégicos orientados a profesionalizar la gestión del producto web y asegurar una ejecución predecible:

### 1. Definición de Alcance & Arquitectura de Información
* Investigar el mercado de turismo en España para identificar mejores prácticas de UX/UI.
* Consolidar los requerimientos funcionales y de negocio en un **PRD** estructurado en Notion.
* Diseñar la nueva arquitectura de información y la navegación del portal para canales B2C y B2B.

### 2. Planificación Estratégica & WBS (Estructura de Desglose de Trabajo)
* Desglosar el proyecto en módulos funcionales y entregables medibles a lo largo de un ciclo de 8 semanas.
* Mapear la **WBS** para coordinar los esfuerzos del equipo de desarrollo, diseño y analítica.
* Definir criterios de aceptación claros para el control de calidad (QA) antes de la puesta en producción.

### 3. Gestión Ágil & Medición de Rendimiento
* Estructurar el backlog y el flujo de trabajo en **Trello (Kanban)** para asegurar la transparencia del proceso de desarrollo.
* Diseñar el plan de medición de eventos en **Google Analytics 4 (GA4)** para evaluar la adopción del portal y el embudo de conversión.
* Establecer un modelo de gobernanza que garantice la entregabilidad dentro del presupuesto y plazos acordados.

---

## 3. Estructura del Proyecto y Herramientas (Project Framework & Artifacts)

La gestión y documentación de este proyecto se estructuró a través de un ecosistema de herramientas de Project Management para garantizar la trazabilidad, la colaboración fluida y la alineación entre las partes interesadas (Stakeholders) y el equipo técnico.

### Documentación Central (Notion)

Es el repositorio principal de conocimiento del proyecto donde se centralizó la estrategia y la definición funcional:
* **Project Charter:** Define la justificación del negocio, los objetivos estratégicos, el alcance inicial, las restricciones y los criterios de éxito de la reestructuración web.
* **PRD (Documento de Requerimientos de Producto):** Detalla las especificaciones funcionales B2C y B2B, los flujos de usuario, las historias de usuario (*User Stories*) y las reglas de negocio para el canal de agencias.
* **Arquitectura de Información (IA):** Mapeo de la navegación del sitio, jerarquía de páginas y mapas de experiencia de usuario (User Journeys).

### Estructura de Desglose de Trabajo (WBS)

Herramienta jerárquica utilizada para descomponer el proyecto a 8 semanas en bloques de trabajo gestionables:
* **Módulos Funcionales:** Investigación & Estrategia, Experiencia de Usuario (UX/UI), Desarrollo WordPress, Portal B2B, Integraciones y Calidad (QA).
* **Entregables Medibles:** Cada paquete de trabajo cuenta con criterios de aceptación claros y entregables definidos para eliminar la ambigüedad en la fase de desarrollo.

### Gestión Ágil de Flujos (Trello Kanban)

Tablero visual utilizado para la planificación y seguimiento del backlog de ejecución:
* **Flujo de Trabajo (Workflow):** Organizado en columnas de *Backlog, En Proceso (In Progress), En Revisión/QA (Review)* y *Completado (Done)*.
* **Asignación de Tareas:** Tarjetas de tareas derivadas de la WBS con etiquetas por nivel de prioridad, dependencias técnicas y listas de verificación (*Checklists*).

### Métricas & Control de Calidad (Google Analytics 4 & QA)

Plan de medición y trazabilidad diseñado para validar el rendimiento del nuevo portal:
* **Plan de Eventos GA4:** Mapeo de eventos personalizados para medir la conversión del embudo B2C y la adopción del portal B2B por parte de las agencias.
* **Matriz QA:** Lista de comprobación para pruebas funcionales, rendimiento *mobile* y validación de flujos comerciales antes de la puesta en producción.

---

# ✈️ Project Charter & WBS: Reestructuración Web B2C/B2B - Empresa X

## 1. Resumen & Objetivo del Proyecto
Liderar la reestructuración integral del sitio web e-commerce de una empresa del sector turismo en España (Empresa X) sobre WordPress. El objetivo es optimizar la plataforma para responder a una doble dinámica comercial: captación directa de clientes particulares (B2C) y facilitación del canal de venta para agencias minoristas colaboradoras (B2B), incrementando la conversión y reduciendo la carga operativa mediante funciones de autoservicio y analítica avanzada (GA4).

## 2. Alcance del Proyecto (Alcance Funcional)
* **Visualización de Paquetes & UX:**
  * Rediseño de fichas de viajes limpias con badges de duración, precio e íconos de servicios (vuelo/hotel/traslado).
  * Ficha detallada con navegación por 4 pestañas: Descripción, Detalles, Precios e Itinerario.
  * Sistema de itinerarios en formato desplegable (acordeón día por día), mapas de ruta y galería.
* **Segmentación B2C / B2B:**
  * Flujo diferenciado de reserva/login para Cliente Particular (PVP) vs. Agencia Minorista (Tarifa Neta/Comisión).
  * Generación de itinerarios PDF descargables: Versión estándar (B2C) y versión "Marca Blanca" sin branding ni datos de contacto de Empresa X, exclusiva para agencias logueadas.
* **Disparadores de Conversión & Generación de Confianza:**
  * Módulo de reseñas verificadas de Google y métrica social (+5.000 clientes).
  * Sección "Quiénes Somos" con fotos reales del equipo y fotos de grupos de viaje.
  * Indicadores de urgencia/disponibilidad en tiempo real ("Últimas plazas disponibles").
  * Botón flotante de WhatsApp, sección FAQ / Chatbot y guías post-reserva descargables.
* **Analítica & Medición:**
  * Configuración de eventos en Google Analytics 4 (GA4) para medir clics B2C vs B2B, interacción con acordeones de itinerario y descargas de PDFs.

## 3. Equipo & Roles
* **Coordinador de Proyecto / Product Owner:** Gonzalo Rodriguez Spuch *(Investigación UX/UI, levantamiento de requerimientos, QA y seguimiento con desarrolladores)*.
* **Sponsor / Cliente Interno:** Dirección General / Stakeholders *(Aprobación de la visión y decisiones comerciales)*.
* **Consultor / Desarrollador IT:** Equipo externo WordPress *(Implementación de componentes, roles de usuario, PDFs dinámicos y eventos GA4)*.

## 4. Plazo & Presupuesto Estimado
* **Duración:** 8 semanas.
* **Presupuesto:** €3.500 (desarrollo, plugins de roles/PDFs y setup de GA4).

---

## Estructura de Desglose de Trabajo (WBS - Empresa X)

### Módulo 0: Investigación de Mercado & Benchmarking UX/UI
- [x] Análisis comparativo de principales plataformas B2C/B2B de turismo en España.
- [x] Identificación de patrones visuales de éxito (fichas limpias, acordeones, confianza y PDF en marca blanca).
- [x] Redacción y consolidación del documento PRD con propuestas de mejora para Empresa X.

### Módulo 1: Rediseño de Fichas de Viaje & UX
- [x] Definición de tarjetas limpias de oferta (días, precio, íconos vuelo/hotel/traslado).
- [x] Maquetación de la ficha de viaje con 4 pestañas (Descripción, Detalles, Precios, Itinerario).
- [ ] Desarrollar sistema de acordeón desplegable para el itinerario día a día.
- [ ] Integración de mapa de ruta y galería de fotos.

### Módulo 2: Portal de Agencias & Descarga de PDFs
- [ ] Implementar popup/doble botón de segmentación (Particular vs Agencia Minorista).
- [ ] Configuración de roles de usuario en WordPress para agencias (Tarifa neta visible).
- [ ] Desarrollo de descarga de PDF estándar (público).
- [ ] Desarrollo de PDF en "Marca Blanca" (sin logos) restringido a usuarios tipo Agencia.

### Módulo 3: Elementos de Confianza & Conversión
- [ ] Integración de widget de reseñas de Google y contador de viajeros.
- [ ] Maquetación de la sección "Equipo / Quiénes Somos" y galería de grupos.
- [ ] Implementación de avisos de disponibilidad en tiempo real ("Últimas 5 plazas").
- [ ] Añadir botón de WhatsApp, sección FAQ y guías de preparación post-reserva.

### Módulo 4: Analítica Web & Pruebas QA
- [ ] Setup de Google Analytics 4 (GA4) y tracking de eventos (clics B2B/B2C, acordeones, PDFs).
- [ ] Pruebas de usabilidad mobile y testeo del flujo de reserva de agencias.
- [ ] Validación final con Dirección y paso a producción.



---

![Tablero Trello](trello-empresa-x.png)
