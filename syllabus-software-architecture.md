# Syllabus — Arquitectura de Software (16 Semanas)

**Nivel:** Básico → Intermedio  
**Formato:** 2 sesiones/semana · Laboratorio incluido por módulo

---

## Descripción General

Este curso guía a los estudiantes desde los principios fundamentales hasta el pensamiento arquitectónico aplicado. Cubre la distinción entre diseño y arquitectura, el rol del arquitecto, la modularidad, los principales estilos arquitectónicos, el diagramado, los atributos de calidad y la influencia de los datos en las decisiones arquitectónicas. Las semanas finales se enfocan en tendencias de la industria y presentaciones de proyectos estudiantiles.

---

## Prerrequisitos

- Puede identificar los componentes principales de un sistema de software (bases de datos, servidores, interfaces de usuario)
- Puede implementar un sistema simple en al menos un lenguaje de programación
- Conoce las etapas del ciclo de vida del desarrollo de software (requerimientos, diseño, implementación, pruebas, mantenimiento)

---

## Evaluación

| Actividad | Porcentaje |
|---|---|
| Informes de laboratorio (uno por módulo) | 30% |
| Examen parcial (al finalizar el Módulo 4) | 20% |
| Documentación arquitectónica (entregable Módulo 5) | 15% |
| Proyecto final — diseño y presentación | 35% |

---

## Estructura de Módulos y Semanas

---

### Módulo 1 — Arquitectura vs. Diseño `Semana 1`

**Objetivos de Aprendizaje:**
- Explicar las diferencias clave entre arquitectura de software y diseño de software
- Describir el concepto de pensamiento arquitectónico
- Reconocer dónde terminan las decisiones arquitectónicas y comienzan las de diseño

**Temas:**
- 1.1 Introducción a la Arquitectura de Software
- 1.2 Pensamiento Arquitectónico
- 1.3 Arquitectura vs. Diseño — dónde se traza la línea

**Laboratorio 1:** Dada una aplicación web de comercio electrónico sencilla, clasifique una lista de 20 decisiones como *arquitectónicas* o *de diseño*. Justifique cada clasificación con una justificación escrita (1 página).

---

### Módulo 2 — ¿Qué es un Arquitecto de Software? `Semana 2`

**Objetivos de Aprendizaje:**
- Describir las expectativas y responsabilidades de un arquitecto de software
- Distinguir entre profundidad técnica y amplitud técnica
- Reflexionar sobre el rol del arquitecto dentro de un equipo de desarrollo

**Temas:**
- 2.1 Expectativas de un Arquitecto de Software
- 2.2 Profundidad Técnica vs. Amplitud Técnica

**Laboratorio 2:** Ejercicio de autoevaluación — mapee su conocimiento técnico actual en un diagrama de profundidad/amplitud. Identifique 3 áreas a fortalecer para crecer hacia el rol de arquitecto. Presente los hallazgos en una reflexión de 1 página.

---

### Módulo 3 — Modularidad y Diseño Modular `Semana 3`

**Objetivos de Aprendizaje:**
- Definir la modularidad de software y articular sus beneficios
- Identificar las dimensiones de la arquitectura de software
- Analizar la cohesión y el acoplamiento en una estructura de sistema dada

**Temas:**
- 3.1 Las Dimensiones de la Arquitectura de Software
- 3.2 Fundamentos de cohesión y acoplamiento
- 3.3 Beneficios del diseño modular

**Laboratorio 3:** Dado un diagrama de base de código monolítica simplificada, identifique los límites lógicos de los módulos. Mida y puntúe la cohesión y el acoplamiento de cada módulo propuesto. Proponga una refactorización para mejorar la modularidad.

---

### Módulo 4 — Estilos Arquitectónicos `Semanas 4–7`

**Objetivos de Aprendizaje:**
- Identificar y describir 8 estilos arquitectónicos principales
- Reconocer las fortalezas y debilidades de cada estilo
- Seleccionar el estilo apropiado para un conjunto dado de requerimientos

#### Semana 4 — Introducción a los Estilos · Capas · Monolito Modular

| Lección | Contenido |
|---|---|
| 4.1 | Introducción a los Estilos Arquitectónicos |
| 4.2 | Arquitectura en Capas |
| 4.3 | Monolito Modular |

#### Semana 5 — Microkernel · Microservicios

| Lección | Contenido |
|---|---|
| 4.4 | Arquitectura Microkernel |
| 4.5 | Arquitectura de Microservicios |

#### Semana 6 — Basada en Servicios · Orientada a Eventos

| Lección | Contenido |
|---|---|
| 4.6 | Arquitectura Basada en Servicios |
| 4.7 | Arquitectura Orientada a Eventos |

#### Semana 7 — Basada en Espacio · Comparación y Repaso

| Lección | Contenido |
|---|---|
| 4.8 | Arquitectura Basada en Espacio |
| 4.9 | Revisión comparativa de los 8 estilos |

**Examen Parcial** — Fin de la Semana 7 (cubre Módulos 1–4)

**Laboratorio 4:** Diseñe el mismo problema (una plataforma de transporte compartido) utilizando **dos estilos arquitectónicos diferentes** de su elección. Para cada diseño, documente: componentes, interacciones y 3 compromisos (*trade-offs*). Presente una recomendación final con justificación.

---

### Módulo 5 — Diagramado `Semana 8`

**Objetivos de Aprendizaje:**
- Crear diagramas que representen con precisión la estructura y el comportamiento de un sistema
- Aplicar el modelo C4 (Contexto, Contenedor, Componente, Código)
- Usar diagramas como herramienta de comunicación con partes interesadas técnicas y no técnicas

**Temas:**
- 5.1 Por qué los diagramas importan en arquitectura
- 5.2 El Modelo C4 — niveles y uso
- 5.3 UML para arquitectura — diagramas de secuencia, componentes y despliegue
- 5.4 Registros de Decisiones Arquitectónicas (ADR)

**Laboratorio 5:** Dada una descripción escrita de un sistema de entrega de comida, elabore un **diagrama C4 completo** (niveles Contexto + Contenedor) usando cualquier herramienta de diagramado (draw.io, Structurizr, Miro, etc.). Escriba también un ADR para la decisión arquitectónica más crítica tomada.

---

### Módulo 6 — Características Arquitectónicas `Semanas 9–10`

**Objetivos de Aprendizaje:**
- Definir y clasificar las características arquitectónicas (requerimientos no funcionales)
- Identificar y priorizar características para un sistema específico
- Reconocer cómo las características influyen y restringen las decisiones arquitectónicas

#### Semana 9 — Comprensión de las Características Arquitectónicas

| Tema | Contenido |
|---|---|
| 6.1 | ¿Qué son las características arquitectónicas? |
| 6.2 | Características implícitas vs. explícitas |
| 6.3 | Características operacionales: disponibilidad, escalabilidad, rendimiento |

#### Semana 10 — Aplicación de las Características Arquitectónicas

| Tema | Contenido |
|---|---|
| 6.4 | Características estructurales: mantenibilidad, modularidad, extensibilidad |
| 6.5 | Características transversales: seguridad, usabilidad, observabilidad |
| 6.6 | Priorización de características — análisis de compromisos (introducción al ATAM) |

**Laboratorio 6:** Aplique un **ATAM simplificado (Método de Análisis de Compromisos Arquitectónicos)** a un sistema real de su elección (p. ej., Spotify, WhatsApp, un sistema empresarial interno). Identifique las 5 principales características arquitectónicas, puntúelas y documente los compromisos clave en un informe estructurado.

---

### Módulo 7 — Los Datos en la Arquitectura de Software `Semanas 11–12`

**Objetivos de Aprendizaje:**
- Explicar cómo los requerimientos de datos influyen en las decisiones arquitectónicas
- Comparar patrones de topología de datos y cuándo usar cada uno
- Seleccionar los tipos de bases de datos apropiados según los requerimientos del sistema

#### Semana 11 — Cómo los Datos Influyen en la Arquitectura

| Tema | Contenido |
|---|---|
| 7.1 | El rol de los datos en la definición de la arquitectura |
| 7.2 | Propiedad de los datos en sistemas distribuidos |
| 7.3 | Topologías de datos: centralizada, federada, distribuida |

#### Semana 12 — Tipos de Bases de Datos y Patrones de Datos

| Tema | Contenido |
|---|---|
| 7.4 | Bases de datos relacionales — cuándo y por qué |
| 7.5 | Bases de datos de documentos, clave-valor, grafos, series de tiempo |
| 7.6 | Persistencia políglota — elegir la herramienta correcta |

**Laboratorio 7:** Diseñe la capa de datos completa para una plataforma de redes sociales. Elija un tipo de base de datos para cada dominio (usuarios, publicaciones, relaciones, registros de actividad). Justifique cada elección frente a las características arquitectónicas del sistema. Entregue un diagrama de topología de datos y una justificación de 1 página.

---

### Módulo 8 — Tendencias de la Industria y Casos de Estudio `Semanas 13–14`

**Objetivos de Aprendizaje:**
- Describir las tendencias actuales y emergentes que configuran la arquitectura de software
- Analizar cómo empresas reales toman decisiones arquitectónicas a escala
- Conectar los conceptos teóricos con sistemas en producción

#### Semana 13 — Tendencias en Arquitectura

| Tema | Contenido |
|---|---|
| 8.1 | Arquitectura nativa de la nube — serverless, contenedores, servicios gestionados |
| 8.2 | Arquitectura para IoT — computación en el borde, gestión de dispositivos, ingesta de datos |
| 8.3 | IA/ML en arquitectura — servicio de modelos, pipelines de datos, integración de LLMs |
| 8.4 | La observabilidad como preocupación arquitectónica |

#### Semana 14 — Casos de Estudio

| Tema | Contenido |
|---|---|
| 8.5 | Netflix — del monolito a microservicios, ingeniería del caos, resiliencia |
| 8.6 | Amazon — descomposición de servicios, equipos de dos pizzas, cultura API-first |
| 8.7 | Discusión: ¿qué podemos aplicar de estos casos a sistemas más pequeños? |

**Sin laboratorio en este módulo** — los estudiantes usan este tiempo para finalizar su proyecto final.

---

### Módulo 9 — Presentaciones del Proyecto Final `Semanas 15–16`

**Objetivo:** Los estudiantes diseñan y defienden una arquitectura de software completa para un problema real de su elección.

**Entregables:**
- Diagrama C4 (niveles Contexto + Contenedor)
- Selección del estilo arquitectónico con justificación
- Priorización de características arquitectónicas (top 5)
- Diseño de la capa de datos con selección del tipo de base de datos
- 2–3 ADRs documentando decisiones críticas
- Presentación de 10 minutos + 5 minutos de preguntas

#### Semana 15 — Presentaciones Grupo A (50% del curso)
#### Semana 16 — Presentaciones Grupo B (50% del curso)

**Criterios de Evaluación:**

| Criterio | Porcentaje |
|---|---|
| Comprensión del problema y claridad de requerimientos | 15% |
| Selección y justificación del estilo arquitectónico | 25% |
| Identificación de atributos de calidad y compromisos | 20% |
| Claridad y completitud del diagramado | 20% |
| Defensa — respuestas a preguntas | 20% |

---

## Resumen Semanal

| Semana | Módulo | Tema |
|---|---|---|
| 1 | Módulo 1 | Arquitectura vs. Diseño |
| 2 | Módulo 2 | ¿Qué es un Arquitecto de Software? |
| 3 | Módulo 3 | Modularidad y Diseño Modular |
| 4 | Módulo 4 | Estilos: Introducción · Capas · Monolito Modular |
| 5 | Módulo 4 | Estilos: Microkernel · Microservicios |
| 6 | Módulo 4 | Estilos: Basada en Servicios · Orientada a Eventos |
| 7 | Módulo 4 | Estilos: Basada en Espacio · Repaso + **Parcial** |
| 8 | Módulo 5 | Diagramado (C4, ADRs) |
| 9 | Módulo 6 | Características Arquitectónicas — Parte 1 |
| 10 | Módulo 6 | Características Arquitectónicas — Parte 2 (ATAM) |
| 11 | Módulo 7 | Datos en Arquitectura — Parte 1 |
| 12 | Módulo 7 | Datos en Arquitectura — Parte 2 |
| 13 | Módulo 8 | Tendencias (Nube, IoT, IA) |
| 14 | Módulo 8 | Casos de Estudio (Netflix, Amazon) |
| 15 | Módulo 9 | Presentaciones Proyecto Final — Grupo A |
| 16 | Módulo 9 | Presentaciones Proyecto Final — Grupo B |
