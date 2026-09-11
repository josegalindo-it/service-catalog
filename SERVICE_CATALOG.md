# SERVICE_CATALOG.md
<!-- SERVICE_CATALOG.md -->

> **Fuente:** `index.html` — web de posicionamiento personal (josegalindo.net)
> **Propósito:** inventario de referencia versionado de todo el contenido editorial de la página, en ES/EN, para facilitar su mantenimiento fuera del HTML/WordPress.
> **Idiomas cubiertos:** Español (ES, idioma por defecto) / Inglés (EN)
> **Estructura de la página:** Cabecera → Servicios Take Away → Pilares de Competencia → Certificaciones Profesionales → Footer
> **Última extracción:** 2026-09-11

---

## Índice

1. [Metadatos globales y CTAs](#1-metadatos-globales-y-ctas)
2. [Cabecera (Header)](#2-cabecera-header)
3. [Servicios Take Away](#3-servicios-take-away)
   - [S1 · Diagnóstico y recuperación de proyecto desviado](#s1--diagnóstico-y-recuperación-de-proyecto-desviado)
   - [S2 · PMO ligera: puesta en marcha del gobierno de proyectos](#s2--pmo-ligera-puesta-en-marcha-del-gobierno-de-proyectos)
   - [S3 · Dirección de proyecto en interim](#s3--dirección-de-proyecto-en-interim)
   - [S4 · Estabilización de servicio y gestión de incidencias](#s4--estabilización-de-servicio-y-gestión-de-incidencias)
   - [S5 · Assessment de madurez y gobierno del dato](#s5--assessment-de-madurez-y-gobierno-del-dato)
4. [Pilares de Competencia](#4-pilares-de-competencia)
5. [Certificaciones Profesionales](#5-certificaciones-profesionales)
6. [Footer](#6-footer)
7. [Notas técnicas de implementación (i18n)](#7-notas-técnicas-de-implementación-i18n)

---

## 1. Metadatos globales y CTAs

| Elemento | Valor |
|---|---|
| `<title>` / `page_title` | José Galindo IT Service Delivery & Governance Leader *(idéntico en ES y EN)* |
| Idioma por defecto | `es` (fallback si no hay preferencia guardada) |
| Selector de idioma | Botones `ES` / `EN` en la cabecera, arriba a la derecha |
| CTA "Agendar Cita" (`btn_book`) | ES: `🗓️ Agendar Cita` · EN: `🗓️ Book a Call` → enlaza a `https://cal.com/jose-galindo/30min` (target `_blank`) |
| CTA "Ver Servicios Take Away" (`btn_services`) | ES: `Ver Servicios Take Away` · EN: `View Take-Away Services` → ancla `#takeaway` |
| CTA "Ver Competencias" (`btn_skills`) | ES: `Ver Competencias` · EN: `View Competencies` → ancla `#competencies` |
| CTA "Contactar" (`btn_contact`) | ES: `Contactar` · EN: `Contact Me` → ancla `#contact` (footer) |

---

## 2. Cabecera (Header)

| Clave i18n | ES | EN |
|---|---|---|
| `badge` | Estrategia & Operaciones IT | IT Strategy & Operations |
| `title` (H1) | IT Service Delivery & Governance Leader | IT Service Delivery & Governance Leader |
| `subtitle` | Liderando la transformación digital, la excelencia operativa e implementación de marcos de gobierno ITIL/COBIT para maximizar el valor de negocio. | Leading digital transformation, operational excellence, and the implementation of ITIL/COBIT governance frameworks to maximize business value. |

---

## 3. Servicios Take Away

Sección ancla `id="takeaway"`. Título de sección (`section_services`): ES *"Servicios Take Away"* / EN *"Take-Away Services"*.

Etiquetas comunes a las 5 fichas de servicio (`lbl_*`):

| Clave | ES | EN |
|---|---|---|
| `lbl_includes` | Incluye | Includes |
| `lbl_excludes` | NO incluye | Out of Scope |
| `lbl_deliv` | Entregables | Deliverables |
| `lbl_evidence` | Evidencia | Evidence |

Cada servicio incluye además un **badge de categoría** no traducido (mismo texto en ES/EN): `PM`, `PM`, `PM / Data`, `PM (SDM)`, `Data`.

---

### S1 · Diagnóstico y recuperación de proyecto desviado

- **ID interno:** `s1` · **Categoría (badge):** `PM`

| Campo | ES | EN |
|---|---|---|
| Título (`s1_title`) | Diagnóstico y recuperación de proyecto desviado | Troubled Project Diagnosis & Recovery |
| Frase del cliente (`s1_prob`) | "Llevamos meses con este proyecto, las fechas se mueven cada mes y no sé si va a salir. El proveedor dice que sí, pero ya no me lo creo." | "We have been on this project for months, dates shift every month and I don't know if it will be delivered. The vendor says yes, but I don't believe them anymore." |
| Incluye (`s1_inc`) | Revisión de alcance, plan y dependencias · entrevistas a equipo interno y proveedor · análisis de desviación de plazo y coste · identificación de causa raíz · plan de recuperación priorizado · cuadro de seguimiento operativo. | Scope, plan, and dependencies review · interviews with internal team and vendor · schedule and cost deviation analysis · root cause identification · prioritized recovery plan · operational tracking dashboard. |
| NO incluye (`s1_exc`) | Ejecución del plan de recuperación (es S3) · auditoría contractual o legal · desarrollo técnico · evaluación de personas. | Execution of the recovery plan (that's S3) · contractual or legal audit · technical development · personnel evaluation. |
| Entregables (`s1_deliv`) | Informe de diagnóstico · plan de recuperación con hitos y responsables · cuadro de mando de seguimiento · sesión de presentación a dirección. | Diagnostic report · recovery plan with milestones and owners · tracking dashboard · executive presentation session. |
| Evidencia (`s1_evi`) | Santander CIB: reingeniería Lean sobre marco ITIL del proceso de valoración, tiempo de respuesta −33% (6→4 días) y SLA de valoración del 75% al 100%, sostenido en ~95% durante 18 meses · Mapfre: reducción del 65% en tasa de fallos en cambios (8,6→3 rechazos/mes), SLA >98% y eliminación de penalizaciones contractuales. | Santander CIB: Lean reengineering on ITIL framework for the valuation process, response time -33% (6→4 days) and valuation SLA improved from 75% to 100%, sustained at ~95% for 18 months · Mapfre: 65% reduction in change failure rate (8.6→3 rejections/month), SLA >98% and elimination of contractual penalties. |
| Duración (`s1_dur`) | 2–3 semanas · 2–3 días por semana | 2–3 weeks · 2–3 days/week |
| Unidad comercial (`s1_unit`) | Paquete cerrado | Fixed-price package |

---

### S2 · PMO ligera: puesta en marcha del gobierno de proyectos

- **ID interno:** `s2` · **Categoría (badge):** `PM`

| Campo | ES | EN |
|---|---|---|
| Título (`s2_title`) | PMO ligera: puesta en marcha del gobierno de proyectos | Light PMO: Project Governance Setup |
| Frase del cliente (`s2_prob`) | "Tenemos ocho cosas en marcha a la vez, cada responsable reporta como quiere, y en el comité de dirección no conseguimos decidir qué es prioritario." | "We have eight things running at once, each manager reports however they want, and in the steering committee we can't decide what's a priority." |
| Incluye (`s2_inc`) | Inventario de portfolio · criterios de priorización · juego mínimo de plantillas (ficha de proyecto, seguimiento, riesgos) · calendario y guion de comité · cuadro de mando ejecutivo · acompañamiento de 2–3 comités piloto. | Portfolio inventory · prioritization criteria · minimal set of templates (project charter, tracking, risks) · committee calendar and agenda · executive dashboard · accompaniment for 2–3 pilot committees. |
| NO incluye (`s2_exc`) | Gestión de los proyectos (es S3) · implantación de herramienta software · rediseño organizativo · definición de procesos fuera del ámbito de proyectos. | Project management (that's S3) · software tool implementation · organizational redesign · definition of non-project processes. |
| Entregables (`s2_deliv`) | Modelo de gobierno operativo (documento de uso, no marco teórico) · set de plantillas · cuadro de mando ejecutivo · actas de los comités piloto. | Operational governance model (usable document, not a theoretical framework) · template set · executive dashboard · pilot committee minutes. |
| Evidencia (`s2_evi`) | BBVA (Everis): diseño e implantación de modelos PMO y gobernanza para la Plataforma Informacional Global, 215.000 horas y 10 proyectos simultáneos, dirigiendo 7 jefes de proyecto bajo modelo de doble supervisión · Repsol (Devoteam): diseño y puesta en marcha de una Service Management Office con KPI/SLA y trazabilidad end-to-end · Santander BMG (Devoteam): reporting ejecutivo y control presupuestario con desviación mantenida por debajo del 10%. | BBVA (Everis): Design and implementation of PMO models and governance for the Global Informational Platform, 215,000 hours and 10 simultaneous projects, directing 7 project managers under a dual-supervision model · Repsol (Devoteam): Design and launch of a Service Management Office with end-to-end KPI/SLA traceability · Santander BMG (Devoteam): Executive reporting and budget control keeping deviation below 10%. |
| Duración (`s2_dur`) | 4–6 semanas · 2 días por semana | 4–6 weeks · 2 days/week |
| Unidad comercial (`s2_unit`) | Paquete cerrado, con opción de acompañamiento mensual posterior | Fixed-price package, with optional monthly follow-up retainer |

---

### S3 · Dirección de proyecto en interim

- **ID interno:** `s3` · **Categoría (badge):** `PM / Data`

| Campo | ES | EN |
|---|---|---|
| Título (`s3_title`) | Dirección de proyecto en interim | Interim Project Management |
| Frase del cliente (`s3_prob`) | "Se nos ha ido el jefe de proyecto" · "no tenemos a nadie con la veteranía para llevar esto y no quiero contratar a alguien fijo todavía." | "Our project manager left" · "We don't have anyone with the seniority to handle this and I don't want to hire someone full-time yet." |
| Incluye (`s3_inc`) | Plan y línea base · coordinación de equipo interno y proveedores · gestión de riesgos y dependencias · seguimiento y reporting a dirección · cierre y traspaso. | Plan and baseline · coordination of internal team and vendors · risk and dependency management · tracking and executive reporting · closure and handover. |
| NO incluye (`s3_exc`) | Responsabilidad jerárquica sobre personal · ejecución técnica · responsabilidad contractual frente al proveedor · sustitución indefinida de un rol de plantilla. | Hierarchical responsibility over staff · technical execution · contractual responsibility regarding the vendor · indefinite substitution of a staff role. |
| Entregables (`s3_deliv`) | Plan vivo · reporting periódico de avance, riesgos y desviación · actas de decisión · documento de cierre y traspaso. | Live plan · periodic progress, risk, and deviation reporting · decision minutes · closure and handover document. |
| Evidencia (`s3_evi`) | **General:** Santander (Atmira): coordinación del Plan DWH-Riesgo de Crédito, 82.000 h/año con 6 factorías, alcanzando el 92% del plan · Liberbank (Atmira): dirección del proyecto regulatorio IAS 39 coordinando tres streams tecnológicos, entregado dentro de plazo regulatorio.<br>**Variante Data:** Santander Consumer (Atmira): programa regulatorio RDA-BI/BCBS 239, 58.000 horas, coordinando 5 factorías externas, ~95% de hitos con desviación <10% · Banc Sabadell: dirección del servicio del ecosistema Big Data corporativo, 18.500 h/año, −80% en incidencias críticas de rendimiento. | **General:** Santander (Atmira): coordination of the DWH-Credit Risk Plan, 82,000 hrs/year with 6 factories, achieving 92% of the plan · Liberbank (Atmira): management of the IAS 39 regulatory project coordinating three tech streams, delivered within regulatory deadlines.<br>**Data Variant:** Santander Consumer (Atmira): RDA-BI/BCBS 239 regulatory program, 58,000 hours, coordinating 5 external factories, ~95% of milestones with deviation <10% · Banc Sabadell: service management for the corporate Big Data ecosystem, 18,500 hrs/year, -80% in critical performance incidents. |
| Duración (`s3_dur`) | 3–6 meses · 2–5 días por semana | 3–6 months · 2–5 days/week |
| Unidad comercial (`s3_unit`) | Bolsa de días al mes | Monthly block of hours/days |

> Nota: el HTML de `s3_evi` contiene formato interno (`<strong>`, `<br><br>`) para distinguir el bloque "General" del bloque "Variante Data" dentro de la misma celda de evidencia.

---

### S4 · Estabilización de servicio y gestión de incidencias

- **ID interno:** `s4` · **Categoría (badge):** `PM (SDM)`

| Campo | ES | EN |
|---|---|---|
| Título (`s4_title`) | Estabilización de servicio y gestión de incidencias | Service Stabilization & Incident Management |
| Frase del cliente (`s4_prob`) | "El servicio se cae, los usuarios están quemados, cada incidencia se gestiona por mensajería y nadie sabe qué pasó la semana pasada." | "The service goes down, users are burnt out, every incident is managed via chat apps, and nobody knows what happened last week." |
| Incluye (`s4_inc`) | Diagnóstico del estado del servicio · modelo de gestión de incidencias (clasificación, prioridades, escalado) · definición de SLA e indicadores realistas · rutina de seguimiento operativo · reporting de servicio · acompañamiento del arranque. | Service status diagnosis · incident management model (classification, priorities, escalation) · definition of realistic SLAs and indicators · operational tracking routine · service reporting · launch accompaniment. |
| NO incluye (`s4_exc`) | Guardia ni cobertura 24×7 · resolución técnica de incidencias · implantación de herramienta de ticketing · gestión del contrato con el proveedor. | On-call or 24x7 coverage · technical resolution of incidents · ticketing tool implementation · vendor contract management. |
| Entregables (`s4_deliv`) | Informe de situación · modelo operativo de incidencias · catálogo de SLA/KPI · cuadro de mando de servicio · rutina de comité operativo en marcha. | Status report · incident operational model · SLA/KPI catalog · service dashboard · active operational committee routine. |
| Evidencia (`s4_evi`) | Mapfre: estabilización del cumplimiento de SLA por encima del 98% mediante reingeniería Lean y taskforces, con eliminación de penalizaciones contractuales y +8% de margen operativo recuperado · Banc Sabadell: −80% en incidencias críticas (de 5 a menos de 1 al mes) mediante mantenimiento preventivo y monitorización proactiva, y +14% de rendimiento operativo · Repsol (Devoteam): implantación de marcos de gobierno operativo ITIL con KPI/SLA end-to-end. | Mapfre: SLA compliance stabilization above 98% through Lean reengineering and taskforces, eliminating contractual penalties and recovering +8% operating margin · Banc Sabadell: -80% in critical incidents (from 5 to less than 1 per month) through preventive maintenance and proactive monitoring, and +14% operational performance · Repsol (Devoteam): implementation of ITIL operational governance frameworks with end-to-end KPI/SLAs. |
| Duración (`s4_dur`) | 3–5 semanas de puesta en marcha · opción de seguimiento mensual ligero | 3–5 weeks setup · optional light monthly tracking |
| Unidad comercial (`s4_unit`) | Paquete cerrado + retainer mensual opcional | Fixed-price package + optional monthly retainer |

---

### S5 · Assessment de madurez y gobierno del dato

- **ID interno:** `s5` · **Categoría (badge):** `Data`

| Campo | ES | EN |
|---|---|---|
| Título (`s5_title`) | Assessment de madurez y gobierno del dato | Data Maturity Assessment & Governance |
| Frase del cliente (`s5_prob`) | "Queremos hacer algo con los datos —o con IA— y no sabemos por dónde empezar. Cada área tiene su hoja de cálculo y ninguna cuadra con la otra." | "We want to do something with data —or AI— and we don't know where to start. Every department has its spreadsheet and none match each other." |
| Incluye (`s5_inc`) | Inventario de fuentes y flujos · identificación de propiedad del dato · evaluación de calidad y de puntos de ruptura · diagnóstico de madurez · roadmap priorizado por valor y esfuerzo · estimación de orden de magnitud de las iniciativas. | Sources and flows inventory · data ownership identification · quality and breaking points evaluation · maturity diagnosis · roadmap prioritized by value and effort · initiative magnitude estimation. |
| NO incluye (`s5_exc`) | Desarrollo de pipelines, modelado o cuadros de mando · selección o implantación de herramienta · ejecución del roadmap (es S3 en su variante Data) · trabajo de analista de datos. | Development of pipelines, modeling, or dashboards · tool selection or implementation · roadmap execution (that's S3 Data variant) · data analyst work. |
| Entregables (`s5_deliv`) | Informe de madurez y diagnóstico · mapa de fuentes y propiedad · roadmap priorizado · presentación ejecutiva a dirección. | Maturity and diagnostic report · sources and ownership map · prioritized roadmap · executive presentation to management. |
| Evidencia (`s5_evi`) | Santander (Atmira): coordinación del Plan DWH-Riesgo de Crédito (82.000 h/año) y del programa RDA-BI/BCBS 239 (58.000 horas), asegurando integridad y trazabilidad del dato para reporting regulatorio · BBVA (Everis): diseño e implantación de modelos de gobernanza para sistemas de datos corporativos globales, incluida supervisión y auditoría metodológica de un sub-portfolio de 150.000 h en BBVA Bancomer · Banc Sabadell: gobierno operativo del ecosistema Big Data corporativo. | Santander (Atmira): Coordination of the DWH-Credit Risk Plan (82,000 hrs/year) and the RDA-BI/BCBS 239 program (58,000 hrs), ensuring data integrity and traceability for regulatory reporting · BBVA (Everis): Design and implementation of governance models for global corporate data systems, including methodological supervision and audit of a 150,000 hr sub-portfolio in BBVA Bancomer · Banc Sabadell: Operational governance of the corporate Big Data ecosystem. |
| Duración (`s5_dur`) | 3–4 semanas · 2 días por semana | 3–4 weeks · 2 days/week |
| Unidad comercial (`s5_unit`) | Paquete cerrado | Fixed-price package |

> ⚠️ **Incidencia detectada en el HTML fuente:** el párrafo estático inicial (`<p data-i18n="s5_deliv">`) usa correctamente *"presentación ejecutiva a dirección"*, pero el valor de `s5_deliv` dentro de `translations.es` en el `<script>` está mal escrito como *"presentation ejecutiva a dirección"* (palabra inglesa suelta en frase española). Esto no se nota mientras la página carga en ES por defecto, pero **se manifestaría si el usuario cambia a EN y vuelve a ES** (el JS reemplaza el texto estático por el del objeto `translations`, introduciendo el error). En este catálogo se ha normalizado a la forma correcta ("presentación"); recomendable corregir la línea `s5_deliv` dentro de `translations.es` en el `index.html`.

---

## 4. Pilares de Competencia

Sección ancla `id="competencies"`. Título de sección (`section_competencies`): ES *"Pilares de Competencia"* / EN *"Core Competencies"*.

Los **títulos de las 4 tarjetas y sus iconos son fijos** (no están en el sistema i18n, mismo texto en ES y EN). Las **descripciones** y **algunas tags** sí están traducidas.

### C1 — ⚙️ IT Governance & Compliance

| Campo | ES | EN |
|---|---|---|
| Descripción (`card1_desc`) | Diseño e implementación de marcos de gobierno alineados con COBIT, ISO 27001 e ISO 20000 para garantizar la alineación estratégica y gestión del riesgo. | Design and implementation of governance frameworks aligned with COBIT, ISO 27001, and ISO 20000 to ensure strategic alignment and risk management. |
| Tags | `COBIT` · `ISO 27001` · Gestión de Riesgos (`tag_risk`) · Auditoría IT (`tag_audit`) | `COBIT` · `ISO 27001` · Risk Management (`tag_risk`) · IT Audit (`tag_audit`) |

### C2 — 📊 Service Delivery Excellence

| Campo | ES | EN |
|---|---|---|
| Descripción (`card2_desc`) | Gestión del ciclo de vida del servicio TI basado en ITIL v4. Definición y supervisión de SLAs/OLAs, gestión de incidentes críticos y mejora continua (CSI). | IT service lifecycle management based on ITIL v4. Definition and monitoring of SLAs/OLAs, critical incident management, and continuous service improvement (CSI). |
| Tags (fijas, no traducidas) | `ITIL v4` · `SLAs / KPIs` · `Incident & Problem Mgmt` · `CSI` | `ITIL v4` · `SLAs / KPIs` · `Incident & Problem Mgmt` · `CSI` |

### C3 — 🤝 Vendor & Stakeholder Management

| Campo | ES | EN |
|---|---|---|
| Descripción (`card3_desc`) | Gestión estratégica de proveedores tecnológicos (RFPs, negociación de contratos, evaluación de rendimiento) y alineación con líderes del negocio. | Strategic management of technology vendors (RFPs, contract negotiation, performance evaluation) and alignment with business leaders. |
| Tags | `Vendor Mgmt` · Negociación (`tag_neg`) · Presupuesto IT (`tag_budget`) · `Stakeholders` | `Vendor Mgmt` · Negotiation (`tag_neg`) · IT Budget (`tag_budget`) · `Stakeholders` |

### C4 — 🚀 Digital Transformation & DevOps

| Campo | ES | EN |
|---|---|---|
| Descripción (`card4_desc`) | Liderazgo de equipos multidisciplinares en entornos híbridos y cloud, fomentando culturas DevOps, agilidad y optimización de costes (FinOps). | Leadership of multidisciplinary teams in hybrid and cloud environments, fostering DevOps cultures, agility, and cost optimization (FinOps). |
| Tags (fijas, no traducidas) | `Agile / Scrum` · `Cloud Operations` · `DevOps Culture` · `FinOps` | `Agile / Scrum` · `Cloud Operations` · `DevOps Culture` · `FinOps` |

---

## 5. Certificaciones Profesionales

Título de sección (`section_certs`): ES *"Certificaciones Profesionales"* / EN *"Professional Certifications"*.
El contenido de las tarjetas **no está traducido** (mismo texto en ambos idiomas):

| Certificación | Entidad emisora |
|---|---|
| ITIL 4 Managing Professional | AXELOS Global Best Practice |
| COBIT 2019 Foundation | ISACA |
| PMP® - Project Management Professional | Project Management Institute |
| CRISC - Risk and Information Systems Control | ISACA |

---

## 6. Footer

- Ancla: `id="contact"`
- Texto (fijo, no traducido, con año dinámico calculado por JS `new Date().getFullYear()`):
  `© {año actual} - José Galindo IT Service Delivery & Governance Leader. All rights reserved.`

---

## 7. Notas técnicas de implementación (i18n)

Para quien mantenga el contenido (o migre a WordPress/otro CMS), conviene conservar estos comportamientos:

- **Mecanismo:** objeto JS `translations = { es: {...}, en: {...} }`; cada elemento traducible lleva un atributo `data-i18n="clave"`. La función `setLanguage(lang)` recorre todos los `[data-i18n]` y sustituye `innerHTML` (en `P`, `SPAN`, `DIV`, `H3`, `STRONG`, `H1`, `H2`, `A`) o `textContent` (resto de tags) según la clave.
- **Persistencia de idioma:** `localStorage.setItem('preferredLang', lang)`; al cargar la página, `localStorage.getItem('preferredLang') || 'es'` decide el idioma inicial. *(Nota: en un contexto de artefacto/vista previa sin `localStorage` persistente esto haría fallback silencioso a `'es'` cada carga; en el hosting real de la web sí persiste.)*
- **HTML embebido en cadenas de traducción:** `s3_evi` usa `<strong>` y `<br><br>` dentro del valor de la clave para diferenciar "General" de "Variante Data" en la misma celda de evidencia — es contenido con marcado, no texto plano.
- **Elementos NO traducidos (idénticos en ES/EN)** — mantener fuera del sistema i18n si se replica esta arquitectura:
  - Títulos e iconos de las 4 tarjetas de Pilares de Competencia.
  - Tags fijas: `COBIT`, `ISO 27001`, `ITIL v4`, `SLAs / KPIs`, `Incident & Problem Mgmt`, `CSI`, `Vendor Mgmt`, `Stakeholders`, `Agile / Scrum`, `Cloud Operations`, `DevOps Culture`, `FinOps`.
  - Badges de categoría de servicio: `PM`, `PM / Data`, `PM (SDM)`, `Data`.
  - Identificadores visuales `S1`–`S5`.
  - Las 4 certificaciones (nombre + entidad emisora).
  - Texto del footer (excepto el año, calculado dinámicamente).
- **Anclas de navegación:** `#takeaway` (inicio de Servicios Take Away), `#competencies` (inicio de Pilares de Competencia), `#contact` (footer).
- **CTA externo:** `https://cal.com/jose-galindo/30min` (único enlace externo de la página, abre en pestaña nueva).

---

## 8. Control de cambios de este catálogo

| Fecha | Cambio |
|---|---|
| 2026-09-11 | Primera extracción completa desde `index.html` (versión con 5 servicios Take Away, 4 pilares de competencia, 4 certificaciones, i18n ES/EN). |

> Este fichero es una **referencia versionada**, no la fuente de renderizado de la web. Si el contenido de `index.html` cambia, actualiza primero el HTML y después sincroniza este documento (o a la inversa, si este documento pasa a ser la fuente editorial y el HTML se regenera desde aquí).
---
<!-- <EOF> SERVICE_CATALOG.md -->