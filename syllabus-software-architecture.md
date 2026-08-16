# Arquitectura de Software — Syllabus (16 Semanas)

**Nivel:** Principiante → Intermedio  
**Formato:** 2 sesiones/semana

---

## Descripción del Curso

Este curso guía a los estudiantes desde los principios fundamentales hasta el pensamiento arquitectónico aplicado. Cubre la distinción entre diseño y arquitectura, el rol del arquitecto, la modularidad, los principales estilos arquitectónicos, el modelado de diagramas, los atributos de calidad y la influencia de los datos en las decisiones arquitectónicas. Las últimas semanas se enfocan en tendencias de la industria y presentaciones de proyectos finales.

---

## Prerrequisitos

- Puede identificar los componentes principales de un sistema de software (bases de datos, servidores, interfaces de usuario)
- Puede implementar un sistema simple en al menos un lenguaje de programación
- Familiarizado con el ciclo de vida del desarrollo de software (requisitos, diseño, implementación, pruebas)

---

## Estructura de Módulos / Semanas

---

### Módulo 1 — Arquitectura vs. Diseño `Semana 1`

**Objetivos de Aprendizaje:**
- Explicar las diferencias clave entre arquitectura de software y diseño de software
- Describir el concepto de pensamiento arquitectónico
- Reconocer dónde terminan las decisiones arquitectónicas y dónde comienzan las decisiones de diseño

**Temas:**
- 1.1 Introducción a la Arquitectura de Software
- 1.2 Pensamiento Arquitectónico
- 1.3 Arquitectura vs. Diseño — dónde se traza la línea

---

### Módulo 2 — ¿Qué es un Arquitecto de Software? `Semana 2`

**Objetivos de Aprendizaje:**
- Describir las expectativas y responsabilidades de un arquitecto de software
- Distinguir entre profundidad técnica y amplitud técnica
- Reflexionar sobre el rol del arquitecto dentro de un equipo de desarrollo

**Temas:**
- 2.1 Expectativas de un Arquitecto de Software
- 2.2 Profundidad Técnica vs. Amplitud Técnica

---

### Módulo 3 — Modularidad y Diseño Modular `Semana 3`

**Objetivos de Aprendizaje:**
- Definir la modularidad en software y articular sus beneficios
- Identificar las dimensiones de la arquitectura de software
- Analizar la cohesión y el acoplamiento en una estructura de sistema dada

**Temas:**
- 3.1 Las Dimensiones de la Arquitectura de Software
- 3.2 Fundamentos de Cohesión y Acoplamiento
- 3.3 Beneficios del diseño modular

---

### Módulo 4 — Estilos Arquitectónicos `Semanas 4–7`

**Objetivos de Aprendizaje:**
- Identificar y describir 8 estilos arquitectónicos fundamentales
- Reconocer las fortalezas y debilidades de cada estilo
- Seleccionar un estilo apropiado para un conjunto de requisitos dado

#### Semana 4 — Introducción a los Estilos · Por Capas · Monolito Modular

| Lección | Contenido |
|---|---|
| 4.1 | Introducción a los Estilos Arquitectónicos |
| 4.2 | Arquitectura por Capas |
| 4.3 | Monolito Modular |

#### Semana 5 — Microkernel · Microservicios

| Lección | Contenido |
|---|---|
| 4.4 | Arquitectura Microkernel |
| 4.5 | Arquitectura de Microservicios |

#### Semana 6 — Orientada a Servicios · Orientada a Eventos

| Lección | Contenido |
|---|---|
| 4.6 | Arquitectura Orientada a Servicios |
| 4.7 | Arquitectura Orientada a Eventos |

#### Semana 7 — Basada en Espacio · Comparación y Repaso

| Lección | Contenido |
|---|---|
| 4.8 | Arquitectura Basada en Espacio |
| 4.9 | Repaso comparativo de los 8 estilos |

**Examen de Mitad de Semestre** — Final de la Semana 7 (cubre los Módulos 1–4)

---

### Módulo 5 — Diagramación `Semana 8`

**Objetivos de Aprendizaje:**
- Crear diagramas que representen con precisión la estructura y el comportamiento de un sistema
- Aplicar el modelo C4 (Contexto, Contenedor, Componente, Código)
- Usar los diagramas como herramienta de comunicación con interesados técnicos y no técnicos

**Temas:**
- 5.1 Por qué los diagramas importan en la arquitectura
- 5.2 El Modelo C4 — niveles y uso
- 5.3 UML para arquitectura — diagramas de secuencia y de componentes
- 5.4 Registros de Decisiones de Arquitectura (ADRs)

---

### Módulo 6 — Características de Arquitectura `Semanas 9–10`

**Objetivos de Aprendizaje:**
- Definir y clasificar las características de arquitectura (requisitos no funcionales)
- Identificar y priorizar características para un sistema específico
- Reconocer cómo las características influyen y restringen las decisiones arquitectónicas

#### Semana 9 — Entendiendo las Características de Arquitectura

| Tema | Contenido |
|---|---|
| 6.1 | ¿Qué son las características de arquitectura? |
| 6.2 | Características implícitas vs. explícitas |
| 6.3 | Características operacionales: disponibilidad, escalabilidad, rendimiento |

#### Semana 10 — Aplicando las Características de Arquitectura

| Tema | Contenido |
|---|---|
| 6.4 | Características estructurales: mantenibilidad, modularidad, extensibilidad |
| 6.5 | Características transversales: seguridad, usabilidad, observabilidad |
| 6.6 | Priorización de características — análisis de compromisos (introducción a ATAM) |

---

### Módulo 7 — Datos en las Arquitecturas de Software `Semanas 11–12`

**Objetivos de Aprendizaje:**
- Explicar cómo los requisitos de datos influyen en las decisiones arquitectónicas
- Comparar patrones de topología de datos y cuándo usar cada uno
- Seleccionar tipos de bases de datos apropiados según los requisitos del sistema

#### Semana 11 — Cómo los Datos Influyen en la Arquitectura

| Tema | Contenido |
|---|---|
| 7.1 | El rol de los datos en la conformación de la arquitectura |
| 7.2 | Propiedad de datos en sistemas distribuidos |
| 7.3 | Topologías de datos: centralizada, federada, distribuida |

#### Semana 12 — Tipos de Bases de Datos y Patrones de Datos

| Tema | Contenido |
|---|---|
| 7.4 | Bases de datos relacionales — cuándo y por qué |
| 7.5 | Bases de datos de documentos, clave-valor, grafos y series de tiempo |
| 7.6 | Persistencia políglota — elegir la herramienta correcta |

---

### Módulo 8 — Tendencias en Arquitectura y Casos de la Industria `Semanas 13–14`

**Objetivos de Aprendizaje:**
- Describir las tendencias actuales y emergentes que moldean la arquitectura de software
- Analizar cómo empresas reales toman decisiones arquitectónicas a escala
- Conectar los conceptos teóricos con sistemas en producción

#### Semana 13 — Tendencias en Arquitectura

| Tema | Contenido |
|---|---|
| 8.1 | Arquitectura nativa en la nube — serverless, contenedores, servicios gestionados |
| 8.2 | Arquitectura IoT — computación en el borde, gestión de dispositivos, ingesta de datos |
| 8.3 | IA/ML en la arquitectura — servicio de modelos, pipelines de datos, integración de LLMs |
| 8.4 | Observabilidad como preocupación arquitectónica |

#### Semana 14 — Casos de Estudio

| Tema | Contenido |
|---|---|
| 8.5 | Netflix — del monolito a los microservicios, ingeniería del caos, resiliencia |
| 8.6 | Amazon — descomposición de servicios, equipos de dos pizzas, cultura API-first |
| 8.7 | Discusión: ¿Qué podemos aplicar de estos casos a sistemas más pequeños? |

---

### Módulo 9 — Presentaciones del Proyecto Final `Semanas 15–16`

**Objetivo:** Los estudiantes diseñan y defienden una arquitectura de software completa para un problema del mundo real de su elección.

**Entregables:**
- Diagrama C4 (niveles de Contexto y Contenedor)
- Selección del estilo arquitectónico con justificación
- Priorización de características de arquitectura (top 5)
- Diseño de la capa de datos con selección del tipo de base de datos
- 2–3 ADRs que documenten decisiones críticas
- Presentación de 10 minutos + 5 minutos de preguntas y respuestas

#### Semana 15 — Presentaciones del Grupo A (50% del curso)
#### Semana 16 — Presentaciones del Grupo B (50% del curso)

**Criterios de Evaluación:**

| Criterio | Peso |
|---|---|
| Comprensión del problema y claridad de los requisitos | 15% |
| Selección del estilo arquitectónico y justificación | 25% |
| Identificación de atributos de calidad y compromisos | 20% |
| Claridad y completitud de los diagramas | 20% |
| Defensa — respuestas en preguntas y respuestas | 20% |

---

## Resumen Semanal

| Semana | Módulo | Tema |
|---|---|---|
| 1 | Módulo 1 | Arquitectura vs. Diseño |
| 2 | Módulo 2 | ¿Qué es un Arquitecto de Software? |
| 3 | Módulo 3 | Modularidad y Diseño Modular |
| 4 | Módulo 4 | Estilos: Introducción · Por Capas · Monolito Modular |
| 5 | Módulo 4 | Estilos: Microkernel · Microservicios |
| 6 | Módulo 4 | Estilos: Orientada a Servicios · Orientada a Eventos |
| 7 | Módulo 4 | Estilos: Basada en Espacio · Repaso + **Examen de Mitad** |
| 8 | Módulo 5 | Diagramación (C4, ADRs) |
| 9 | Módulo 6 | Características de Arquitectura — Parte 1 |
| 10 | Módulo 6 | Características de Arquitectura — Parte 2 (ATAM) |
| 11 | Módulo 7 | Datos en la Arquitectura — Parte 1 |
| 12 | Módulo 7 | Datos en la Arquitectura — Parte 2 |
| 13 | Módulo 8 | Tendencias en Arquitectura (Nube, IoT, IA) |
| 14 | Módulo 8 | Casos de Estudio (Netflix, Amazon) |
| 15 | Módulo 9 | Presentaciones del Proyecto Final — Grupo A |
| 16 | Módulo 9 | Presentaciones del Proyecto Final — Grupo B |
