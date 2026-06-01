# Sistema de Gestión de Inventarios y Ventas — Las Trompetas

> **Asignatura:** Sistemas Empresariales | **Universidad de Caldas**
> **Fecha de Entrega:** 28 de mayo de 2026

## Equipo: Desarrollos Hezbollah

| Integrante | Rol Principal |
|---|---|
| Nicolas Casas Bedoya | Gerente de Proyecto / Frontend Lead |
| Hanner Obando | Analista de Requerimientos |
| Juan Esteban Zapata | QA Lead / Pruebas |
| Juan Blandón | Arquitecto de Software |
| Eduar Stiven Jiménez | Desarrollador Backend |

---

## Descripción del Proyecto

Sistema web centralizado para la automatización de los flujos de **inventario y ventas** de la Discoteca Las Trompetas. Reemplaza el proceso manual de anotaciones en papel por un módulo POS táctil, control de stock en tiempo real y reportes automáticos al cierre de turno.

**Stack Tecnológico:** Angular 17 (PWA) | Node.js 20 + Express | MySQL 8.0

---

## Estructura del Repositorio

```
/proyecto-las-trompetas/
├── README.md                        ← Índice general (este archivo)
├── /01-gestion-proyecto/            ← Project Charter, SMART, Cronograma, Stakeholders
├── /02-requerimientos/              ← RF, RNF, Casos de Uso, Historias de Usuario
├── /03-arquitectura/                ← Flujos As-Is/To-Be, Modelo C4, ADRs, Esquema BD
├── /04-riesgos/                     ← Matriz de Riesgos, Mapa de Calor, Registro
├── /05-calidad/                     ← Plan SQA, Criterios de Aceptación, Pruebas, Checklist
└── /presentacion/                   ← Presentación final PDF/PPT
```

---

## Artefactos por Carpeta

### [01 — Gestión del Proyecto](./01-gestion-proyecto/)

| Artefacto | Descripción |
|---|---|
| [Entregable 01 — Gestión del Proyecto](./01-gestion-proyecto/01_Gestion_Proyecto.docx) | Acta de Constitución, Objetivos SMART, Alcance, Cronograma, Stakeholders y Plan de Gestión |

**Contenido:**
- Acta de Constitución del Proyecto (Project Charter) con firmas de aprobación
- Objetivos SMART (OBJ-01 a OBJ-04) con indicadores de éxito medibles
- Alcance formal: In-Scope y Out-of-Scope con criterios de aceptación
- Cronograma de hitos por fase con responsables (20–28 mayo 2026)
- Matriz de Stakeholders con estrategia de gestión diferenciada
- Plan de Gestión: metodología Scrum, comunicaciones y control de cambios

---

### [02 — Requerimientos](./02-requerimientos/)

| Artefacto | Descripción |
|---|---|
| [Entregable 02 — Requerimientos y Casos de Uso](./02-requerimientos/02_Requerimientos_y_Casos_Uso.docx) | RF, RNF, Casos de Uso, Historias de Usuario y Matriz de Trazabilidad |

**Contenido:**
- 7 Requerimientos Funcionales (RF-01 a RF-07) con ID, prioridad, actor y criterio de aceptación
- 8 Requerimientos No Funcionales (RNF-01 a RNF-08) clasificados por categoría con métricas
- 3 Casos de Uso (CU-01: Registrar Venta, CU-02: Abastecer, CU-03: Reporte Diario)
- 7 Historias de Usuario cubriendo los 3 roles: Bartender, Cajero y Administrador
- Matriz de Trazabilidad RF ↔ CU ↔ HU ↔ RNF

---

### [03 — Arquitectura](./03-arquitectura/)

| Artefacto | Descripción |
|---|---|
| [Entregable 03 — Arquitectura C4 y ADR](./03-arquitectura/03_Arquitectura_C4_y_ADR.docx) | Flujos de proceso, Modelo C4, Esquema BD y Decisiones Técnicas |

**Contenido:**
- Diagrama de Flujo **As-Is** (proceso manual actual con puntos críticos)
- Diagrama de Flujo **To-Be** (proceso automatizado con el sistema)
- **C1 — Contexto:** sistema, actores y sistemas externos
- **C2 — Contenedores:** Frontend (Angular), Backend (Node.js), BD (MySQL)
- **C3 — Componentes:** Auth, Inventory, Sales, Report Component
- Esquema relacional normalizado (3FN): 6 tablas con llaves foráneas
- 4 Architecture Decision Records (ADR-01 a ADR-04) con alternativas y consecuencias

---

### [04 — Riesgos](./04-riesgos/)

| Artefacto | Descripción |
|---|---|
| [Entregable 04 — Gestión de Riesgos](./04-riesgos/04_Riesgos.docx) | Matriz de Riesgos, Mapa de Calor y Registro de Seguimiento |

**Contenido:**
- 6 Riesgos identificados (R01–R06) con probabilidad, impacto, nivel (PxI) y plan de mitigación
- Mapa de Calor (Heat Map) con distribución visual P x I
- Registro de riesgos actualizado durante el ciclo del proyecto (20/05 al 27/05)
- Resumen de estado final: 3 mitigados, 3 activos controlados

---

### [05 — Calidad](./05-calidad/)

| Artefacto | Descripción |
|---|---|
| [Entregable 05 — Aseguramiento de Calidad](./05-calidad/05_Calidad.docx) | Plan SQA, Criterios de Aceptación, Pruebas, Checklist y Lecciones Aprendidas |

**Contenido:**
- Plan de Aseguramiento de Calidad (SQA) con roles y responsabilidades
- 10 Criterios de Aceptación del Sistema (CA-01 a CA-10): funcionales y no funcionales
- 6 tipos de prueba ejecutados: 41 casos totales, 97.6% de tasa de éxito
- Checklist de 25 artefactos del proyecto con estado de conformidad
- Checklist de coherencia entre artefactos (trazabilidad cruzada)
- Lecciones Aprendidas por área (calidad, requerimientos, arquitectura, gestión, usabilidad)

---

### [Presentación](./presentacion/)

| Artefacto | Descripción |
|---|---|
| [Presentación Final](./presentacion/Presentacion_Final.pptx) | Slides de sustentación en formato PDF |

**Contenido de la presentación:**
- Portada: nombre del proyecto, integrantes y grupo
- Problema identificado y justificación
- Objetivos del proyecto
- Alcance y limitaciones (incluye/excluye)
- Requerimientos funcionales y no funcionales
- Propuesta técnica: Stack tecnológico y Modelo C4
- Gestión de riesgos
- Conclusiones y lecciones aprendidas

---

## Checklist General de Entrega

### Gestión del Proyecto
- [x] Acta de constitución del proyecto (Project Charter)
- [x] Objetivos SMART del proyecto
- [x] Alcance del proyecto definido y documentado
- [x] Cronograma / plan de trabajo
- [x] Matriz de interesados (Stakeholders)
- [x] Plan de gestión del proyecto

### Requerimientos
- [x] Requerimientos funcionales (RF) con ID, descripción, prioridad y criterio de aceptación
- [x] Requerimientos no funcionales (RNF) clasificados por categoría
- [x] Casos de uso con descripción, actores, flujo principal y flujos alternativos
- [x] Historias de usuario con criterios de aceptación

### Arquitectura
- [x] Diagrama de Flujo As-Is
- [x] Diagrama de Flujo To-Be
- [x] Contexto C1
- [x] Contenedores C2
- [x] Componentes C3
- [x] Decisiones de diseño (ADR)

### Gestión de Riesgos
- [x] Matriz de riesgos con identificación, probabilidad, impacto, nivel y plan de mitigación
- [x] Registro de riesgos actualizado durante el ciclo del proyecto

### Calidad
- [x] Plan de aseguramiento de calidad
- [x] Criterios de aceptación del sistema
- [x] Lista de verificación de revisión de artefactos

### Presentación
- [x] Presentación en PDF con todos los contenidos mínimos requeridos

---

## Condiciones Generales Cumplidas

- [x] Repositorio con estructura de carpetas clara y nombres descriptivos
- [x] README.md en la raíz con índice general y enlaces directos a cada artefacto
- [x] Presentación adjunta en formato PDF
- [x] **No se entrega código fuente** — entrega exclusivamente de documentación, diagramas y presentación

---

*Universidad de Caldas | Facultad de Ingeniería | Sistemas Empresariales | 2026*
*Equipo Desarrollos Hezbollah — Nicolas Casas | Hanner Obando | Juan Zapata | Juan Blandón | Eduar Jiménez*
