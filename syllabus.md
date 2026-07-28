# Propuesta de Syllabus — Desarrollo Front-End

> Curso semestral (~16 semanas, 3–4 horas/semana).

## Objetivo general del curso

Al finalizar el curso, el estudiante será capaz de **diseñar, construir, consumir datos y desplegar** una interfaz web moderna, responsiva y de calidad profesional, usando un framework de componentes (React) y las prácticas actuales de la industria.

## Prerrequisitos (auto-diagnóstico)

La primera semana se entrega una **rúbrica de auto-evaluación**, no solo una lista de temas asumidos como sabidos. Esto permite:
- Tener visibilidad real de las brechas del grupo.
- Decidir si se necesita una semana 0 de nivelación grupal.

Temas a incluir en esa rúbrica: arquitectura cliente-servidor, HTTP/HTTPS, DNS, HTML5 semántico, CSS3 (selectores, box model, cascada), y **Git/GitHub básico** (transversal a todo el curso — sin control de versiones no hay forma de evaluar entregas de forma seria).

---

## Estructura por módulos

### Módulo 1 — Fundamentos web y control de versiones (semana 1-2)
**Al terminar este módulo, el estudiante podrá:**
- Explicar el ciclo cliente-servidor y el rol de HTTP en la comunicación web
- Diagnosticar sus propios vacíos en HTML5/CSS3 mediante la rúbrica de auto-evaluación
- Gestionar un repositorio Git con commits atómicos y pull requests

Temas:
- Arquitectura web, HTTP/HTTPS, ciclo request-response
- Revisión guiada de HTML5/CSS3 (breve, orientada a detectar vacíos, no a enseñar desde cero)
- **Git y GitHub**: commits, branches, pull requests, flujo de trabajo colaborativo
- *Autorrevisión:* antes de entregar, el estudiante compara su repo contra un checklist de buenas prácticas de commits (mensajes claros, historial legible)
- *Entregable:* repositorio personal con página estática, historial de commits limpio

### Módulo 2 — Diseño responsive y CSS moderno (semana 3-4)
**Al terminar este módulo, el estudiante podrá:**
- Construir layouts responsivos con Flexbox y CSS Grid sin depender de un framework
- Aplicar un enfoque mobile-first usando media queries y unidades relativas
- Justificar cuándo conviene usar un framework de CSS y cuándo el CSS nativo es suficiente

Temas:
- Flexbox y CSS Grid a fondo
- Mobile-first, media queries, unidades relativas (rem, %, vw/vh)
- Un framework de utilidades (Tailwind) o de componentes (Bootstrap) — decisión del profesor, igual que React
- Introducción a diseño de sistemas visuales (design tokens, consistencia)
- *Autorrevisión:* el estudiante prueba su maquetación en 3 anchos de pantalla distintos y documenta qué ajustó y por qué
- *Entregable:* maquetación responsiva de un diseño dado (Figma → código)

### Módulo 3 — JavaScript aplicado (semana 5-7)
**Al terminar este módulo, el estudiante podrá:**
- Escribir código asíncrono legible usando Async/Await en vez de callbacks anidados
- Consumir una API externa con Fetch y manejar sus posibles errores en la UI
- Estructurar código JavaScript en módulos reutilizables

Temas:
- ES6+: destructuring, spread/rest, arrow functions, módulos (import/export)
- Manipulación del DOM y eventos
- Asincronía: callbacks → Promesas → Async/Await
- Fetch API y manejo de JSON
- Manejo de errores en código asíncrono
- *Autorrevisión:* el estudiante fuerza un error de red a propósito (API caída, timeout) y verifica que su app no se rompe silenciosamente
- *Entregable:* mini-app que consume una API pública sin framework aún

### Módulo 4 — Framework de componentes: React (semana 8-11)
**Al terminar este módulo, el estudiante podrá:**
- Descomponer una interfaz en componentes reutilizables con props bien definidas
- Elegir correctamente entre estado local y estado global según el caso de uso
- Construir una SPA con navegación entre vistas y formularios validados

Temas:
- JSX, componentes funcionales, props
- Hooks (useState, useEffect, useContext, custom hooks)
- Manejo de estado: local vs. global (Context API, o Zustand/Redux si el tiempo alcanza)
- Enrutamiento (React Router)
- Formularios controlados y validación
- *Autorrevisión:* el estudiante identifica al menos un componente que debería dividirse en dos y lo refactoriza antes de entregar
- *Entregable:* SPA multi-vista con navegación y estado compartido

### Módulo 5 — Consumo de APIs (semana 12-13)
**Al terminar este módulo, el estudiante podrá:**
- Integrar autenticación basada en tokens (JWT) en una aplicación React
- Diseñar los tres estados de una UI que consume datos externos: cargando, vacío y error
- Explicar en qué escenarios GraphQL sería preferible sobre REST

Temas:
- REST en profundidad: verbos, status codes, headers
- Autenticación (JWT, OAuth básico) desde el front-end
- Manejo de estados de carga/error en UI (loading, empty, error states)
- Mención de GraphQL como alternativa (aunque sea conceptual, sin profundizar)
- *Autorrevisión:* el estudiante verifica que su app maneja correctamente un token expirado o una respuesta 401
- *Entregable:* integración de autenticación + CRUD contra una API real o mockeada

### Módulo 6 — Despliegue (semana 13-16)
**Al terminar este módulo, el estudiante podrá:**
- Configurar variables de entorno y un pipeline de build para producción
- Desplegar una aplicación React a un proveedor cloud (Vercel/Netlify)
- Configurar un flujo de CI básico que corra lint y tests automáticamente en cada PR

Temas:
- Build tools (Vite) y variables de entorno
- Despliegue en Vercel/Netlify o similar
- Introducción a CI/CD (GitHub Actions: lint + test automático en cada PR)
- *Autorrevisión:* el estudiante verifica que su app desplegada funciona igual que en local (variables de entorno, rutas, build de producción)
- *Entregable final:* proyecto integrador desplegado y documentado (README con instrucciones)

---

## Proyecto integrador

En lugar de que cada módulo tenga solo un entregable aislado, se recomienda un **único proyecto que crece módulo a módulo** (ej. una app de gestión de tareas, un catálogo con auth, etc.). Esto:
- Refuerza la relación entre los temas del curso.
- Facilita evaluar progreso real vs. ejercicios sueltos.
- Se presta naturalmente para la evaluación final.

## Evaluación

| Componente | Peso |
|---|---|
| Entregables por módulo | 40% |
| Proyecto integrador final | 35% |
| Auto-diagnóstico + participación/code reviews entre pares | 10% |
| Sustentación/demo final | 15% |
