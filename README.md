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
