# 🧑‍💻 Metodologías Ágiles

![Asignatura](https://img.shields.io/badge/Asignatura-Metodolog%C3%ADa%20de%20la%20Programaci%C3%B3n-white)
![Fecha](https://img.shields.io/badge/Fecha-19--09--2025-green)

<div style="text-align: center;">
  <img src="https://www.onplusformacion.com/wp-content/uploads/2021/01/u5_inicio.gif" alt="Metodologías Ágiles" width="400">
</div>

<br>

## 📑 Contenido

| Sección | Tema | Descripción |
|---------|------|------------|
| [1. 📝 Introducción](#-introducción) | — | Qué son las metodologías ágiles y para qué sirven. |
| [2. ❓ Origen](#-qué-son-y-por-qué-surgen) | — | Por qué surgieron y diferencias con métodos tradicionales. |
| [3. 🅿️ Principios Ágiles](#🅿️-principios-ágiles) | Valores y principios | Ideas que guían la forma de trabajar ágilmente. |
| [4. 🛠️ Marcos Ágiles](#️-panorama-de-marcos-ágiles) | — | Presentación de Scrum, Kanban y Design Thinking. |
| [5. 👥 Scrum](#-scrum) | Roles, artefactos y eventos | Cómo funciona Scrum, sus roles, herramientas y reuniones. |
| [6. 🗂️ Kanban](#️-kanban) | Principios y tablero | Gestión visual de tareas, límites WIP y flujo de trabajo. |
| [7. 🤔 Design Thinking](#design-thinking) | Fases y mini-caso | Proceso creativo para entender al usuario y generar soluciones. |
| [8. ⚖️ Cuándo usar cada metodología](#️-cuándo-elegir-cada-metodología-ágil) | — | Situaciones ideales para elegir Scrum, Kanban o DT. |
| [9. ✅ Ventajas y riesgos](#-ventajas-y-riesgos-de-las-metodologías-ágiles) | — | Beneficios, limitaciones y posibles problemas de cada método. |
| [10. 🔚 Conclusiones](#-conclusiones) | — | Reflexión sobre aplicaciones en la vida académica o profesional. |
| [11. 📚 Referencias](#-referencias) | — | Fuentes consultadas y bibliografía utilizada. |

<br>

## 📝 Introducción

En este documento se explorarán las Metodologías Ágiles, un enfoque de gestión y desarrollo de software que prioriza la adaptabilidad, la colaboración y la entrega continua de valor.

Se abordarán los siguientes puntos:

- Qué significa ser “ágil” y por qué surgieron estas metodologías frente a enfoques tradicionales rígidos.

- Los principios y valores fundamentales que guían la práctica ágil.

- Los marcos ágiles más comunes: Scrum, Kanban y Design Thinking, explicando en qué contextos conviene usar cada uno.

- Las ventajas y riesgos de adoptar metodologías ágiles, así como buenas prácticas y limitaciones.

Imagina que vas a organizar un proyecto complejo, como crear una aplicación de control de dispositivos para una casa inteligente. En lugar de planear todo al detalle desde el inicio, las metodologías ágiles te permiten adaptarte a cambios, entregar funcionalidades útiles rápido y aprender de cada iteración para mejorar continuamente el producto final.

El objetivo de este documento es que cualquier lector comprenda de forma clara y sencilla qué son las metodologías ágiles, cómo funcionan en la práctica y cómo aplicarlas en proyectos académicos o profesionales, fomentando una gestión más eficiente y colaborativa del desarrollo de software.

<br>

## ❓ ¿Qué son y por qué surgen?

Las Metodologías Ágiles surgieron como una alternativa a los enfoques tradicionales de desarrollo (como el modelo en cascada), los cuales eran procesos lineales y rígidos que requerían una planificación exhaustiva y documentación detallada al inicio del proyecto. Estos enfoques formales resultaban inefectivos y generaban altos costos cuando el entorno era volátil o los requisitos del cliente cambiaban, lo cual es común en el desarrollo de software.

Ser “ágil” significa adoptar una filosofía de trabajo que prioriza la capacidad de respuesta rápida ante el cambio sobre el seguimiento estricto de un plan predefinido. En lugar de un único producto final planificado de antemano (como firmar un contrato para construir un edificio completo antes de ver nada), las metodologías ágiles trabajan mediante ciclos cortos e iterativos (como si entregaras partes funcionales del producto, por ejemplo, una aplicación con solo la función de inicio de sesión, cada pocas semanas). 

Esto permite entregar software funcional continuamente y recibir la opinión del cliente de manera temprana, asegurando que el producto se ajuste siempre a sus necesidades reales, minimizando el riesgo de construir algo que nadie quiere.

## 🅿️ Principios Ágiles

Las metodologías ágiles se basan en 4 Valores Fundamentales, redactados en el Manifiesto Ágil, que guían la forma de trabajar en proyectos de desarrollo de software. Estos valores se apoyan en 12 principios clave, los cuales influyen directamente en la gestión del trabajo, facilitando colaboración, entrega rápida y mejora continua.

Valores Fundamentales
<details> <summary><b>🧑‍🤝‍🧑 Individuos e interacciones sobre procesos y herramientas</b></summary>

Se prioriza la colaboración y comunicación dentro del equipo. La interacción de las personas es más importante que depender estrictamente de procesos o herramientas.
Impacto en la gestión: fomenta reuniones cortas y efectivas, decisiones rápidas y resolución inmediata de problemas.
Ejemplo práctico: Un desarrollador consulta directamente al cliente sobre una funcionalidad, evitando retrasos por tickets o documentación extensa.

</details>
<details> <summary><b>💻 Software funcionando sobre documentación exhaustiva</b></summary>

La prioridad es entregar software útil y operativo. La documentación se crea solo si es estrictamente necesaria.
Impacto en la gestión: el enfoque se centra en resultados tangibles, evitando que el equipo pierda tiempo en burocracia innecesaria.
Ejemplo práctico: Se entrega una versión mínima funcional (MVP) antes de producir manuales detallados.

</details>
<details> <summary><b>🤝 Colaboración con el cliente sobre negociación contractual</b></summary>

El cliente participa activamente durante todo el proyecto, aportando comentarios y guiando el desarrollo.
Impacto en la gestión: permite priorizar tareas que realmente aportan valor y ajustar rápidamente la planificación según las necesidades del cliente.
Ejemplo práctico: Ajustar la funcionalidad de una aplicación a feedback directo de usuarios antes de su lanzamiento.

</details>
<details> <summary><b>🔄 Respuesta ante el cambio sobre seguir un plan</b></summary>

La flexibilidad y adaptación a cambios son clave. Los cambios se ven como oportunidades para mejorar, no como problemas.
Impacto en la gestión: permite replanificar de forma rápida, reasignar tareas y evitar retrasos significativos cuando surgen nuevos requerimientos.
Ejemplo práctico: Integrar una nueva función solicitada por el cliente durante un sprint sin afectar la entrega del resto del proyecto.

</details>

### 🔑 Principios Clave del Manifiesto Ágil

| Principio                                  | Explicación                                                  | Impacto en la gestión del trabajo                                                                 |
| ------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| Satisfacción del cliente                   | Entregar valor continuamente y temprano.                     | Prioriza tareas que generan valor real; evita esfuerzos innecesarios en funciones poco útiles.    |
| Entregas frecuentes                        | Ciclos cortos de desarrollo con versiones funcionales.       | Facilita retroalimentación constante y ajustes rápidos en la planificación.                       |
| Colaboración diaria                        | Equipos de negocio y desarrollo trabajan juntos.             | Mejora comunicación, reduce errores y evita malentendidos en requisitos.                          |
| Equipos autoorganizados                    | El equipo decide cómo hacer su trabajo.                      | Fomenta responsabilidad, motivación y productividad; el gestor guía en lugar de dictar cada paso. |
| Comunicación cara a cara                   | Preferible a mensajes escritos largos.                       | Permite resolver dudas en tiempo real y tomar decisiones rápidas.                                 |
| Software funcional como medida de progreso | Evita enfocarse solo en documentación o tareas no visibles.  | Gestión basada en resultados concretos, no en procesos burocráticos.                              |
| Ritmo sostenible                           | Mantener un ritmo constante sin sobrecargar al equipo.       | Mejora la eficiencia a largo plazo y evita burnout.                                               |
| Atención continua a la excelencia técnica  | Mejora calidad y simplicidad del software.                   | Reduce retrabajos y errores futuros; mantiene el equipo enfocado en buenas prácticas.             |
| Simplicidad                                | Maximizar el trabajo no realizado; centrarse en lo esencial. | Permite priorizar tareas críticas y reducir desperdicio de tiempo y recursos.                     |
| Retroalimentación y ajuste                 | Revisiones periódicas del proceso y producto.                | Permite identificar problemas a tiempo y mejorar procesos continuamente.                          |
| Entrega de valor                           | Cada iteración debe producir software útil.                  | Facilita planificación iterativa, mejora la satisfacción del cliente y la motivación del equipo.  |
| Adaptación al cambio                       | Cambiar de rumbo si es necesario según feedback.             | La gestión se mantiene flexible, minimizando impactos negativos en tiempo y presupuesto.          |

<br>

## 🛠️ Panorama de Marcos Ágiles

Las metodologías ágiles no son un único proceso, sino un conjunto de marcos y enfoques que ayudan a los equipos a gestionar proyectos de software de manera flexible, colaborativa y eficiente. Cada marco tiene principios, prácticas y herramientas propias, pero todos comparten la filosofía ágil: entregar valor temprano, adaptarse al cambio y mejorar continuamente.

En este panorama nos enfocaremos en tres de los marcos más usados en la industria y en proyectos académicos: Scrum, Kanban y Design Thinking. Cada uno aporta ventajas específicas según el tipo de proyecto, el ritmo de trabajo y el nivel de incertidumbre o complejidad.

> A continuación veremos una descripción de cada metodología, sus elementos clave y cómo se aplican en la práctica, dejando la explicación de cuándo elegir cada una para el cierre de esta sección.

<br>

## 👥 SCRUM

<div style="text-align: center;">
  <img src="https://miro.medium.com/v2/1*D_mKuI449H0TP20Ee07nxg.gif" alt="Metodologías Ágiles" width="300">
</div>
<br>

**Scrum** es una de las metodologías ágiles más utilizadas. Permite a los equipos organizarse de manera autónoma y entregar valor de forma rápida y continua. Se basa en un enfoque iterativo e incremental, dividiendo el trabajo en ciclos cortos llamados Sprints, con entregas funcionales al final de cada ciclo.

---
### 🔠 Características principales:

- **Basada en roles claros:** Stakeholders, Scrum Master, Product Owner y Development Team.

- **Incremental:** El trabajo se entrega en pequeñas partes funcionales llamadas incrementos.

- **Sprints:** Ciclos de 1 a 4 semanas que incluyen planificación, desarrollo y revisión.

- **Dailys (Reuniones diarias):** Breves reuniones para sincronizar al equipo y resolver impedimentos.

---
### 👲 Roles en SCRUM:

#### <b>👑 Product Owner</b>

- Conoce la visión del producto y necesidades del cliente.

- Mantiene y prioriza el Product Backlog.

- Participa en planificación, revisión y retrospectiva del Sprint.

- **Objetivo:** maximizar el valor entregado por el equipo.

- **Errores frecuentes:** priorizar mal las tareas, no comunicarse con stakeholders.

#### <b>🧑‍💼 Scrum Master</b>

- Facilita la aplicación de Scrum y protege al equipo de interrupciones.

- Elimina obstáculos y asegura que se sigan los procesos correctamente.

- Promueve mejora continua y colaboración.

- **Errores frecuentes:** microgestionar al equipo, saltarse eventos clave.

#### <b>💻 Development Team</b>

- Equipo autoorganizado y multidisciplinario (5–9 personas recomendadas).

- Realiza estimaciones, planificación y ejecución de tareas del Sprint.

- **Errores frecuentes:** no actualizar tareas en el tablero, poca comunicación interna.

#### <b>🧑‍🤝‍🧑 Stakeholders</b>

- Personas o grupos interesados en el proyecto: clientes, usuarios, gerentes, inversores.

- Proporcionan feedback y validan valor de entregables.

- No gestionan el día a día del equipo.

---

### 📝 Artefactos de Scrum

| Artefacto                   | Descripción                                                                                     | Criterios de calidad / Nota                                                                                             |
| --------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **Product Backlog**         | Lista priorizada de tareas, funcionalidades, mejoras y bugs.                                    | Debe ser clara, priorizada y revisada continuamente.                                                                    |
| **Sprint Backlog**          | Subconjunto de tareas del Product Backlog que el equipo se compromete a completar en un Sprint. | Selección realista según capacidad del equipo; tareas bien definidas.                                                   |
| **Increment**               | Producto funcional entregable al final del Sprint.                                              | Cumple **Definition of Done (DoD)**: código revisado, probado, documentación mínima, desplegable en ambiente de prueba. |
| **Criterios de aceptación** | Condiciones que una historia/tarea debe cumplir para considerarse completa.                     | Cada historia debe tener criterios claros y verificables; DoD es global para todo el equipo.                            |

---

### 🗓️ Eventos en Scrum

| Evento                   | Objetivo                                                 | Duración sugerida            | Antipatrón típico                                                 |
| ------------------------ | -------------------------------------------------------- | ---------------------------- | ----------------------------------------------------------------- |
| **Sprint**               | Ciclo de trabajo completo con entrega de valor.          | 1–4 semanas                  | Sprint demasiado largo o sin entregables funcionales.             |
| **Sprint Planning**      | Selección de tareas para el Sprint.                      | 2–4 h por semana de Sprint   | Saltarse planificación, comprometer tareas irreales.              |
| **Daily Scrum**          | Sincronizar al equipo y detectar impedimentos.           | 15 min diarios               | Solo reporte de status, sin resolver bloqueos.                    |
| **Sprint Review**        | Presentar incrementos a stakeholders y recibir feedback. | 1–2 h por semana de Sprint   | Mostrar trabajo incompleto o ignorar comentarios de stakeholders. |
| **Sprint Retrospective** | Reflexionar y mejorar procesos del equipo.               | 1–1.5 h por semana de Sprint | Saltarse retrospectiva, no aplicar mejoras identificadas.         |

---

### 📊 Flujo de Scrum y Tablero

### Visualización básica

| 📥 Product Backlog | 📝 To Do | ⚙️ In Progress | ⛔ Blocked | ✅ Done  |
| ------------------ | -------- | -------------- | --------- | ------- |
| Historia 1         | Tarea A  | Tarea B        | Tarea C   | Tarea D |
| Historia 2         | Tarea E  |                |           |         |


### Flujo de trabajo resumido

1. Creación de tareas → Product Owner identifica necesidades y genera historias.

2. Priorización → Product Owner ordena según valor y urgencia.

3. Planificación del Sprint → Development Team selecciona tareas y las traslada al Sprint Backlog.

4. Ejecución y seguimiento → Dailys y tablero permiten sincronización diaria.

5. Revisión y entrega → Increment funcional presentado en Sprint Review.

6. Retroalimentación y mejora → Sprint Retrospective ajusta procesos para el próximo ciclo.

---

### 📈 Métricas clave

| Métrica                    | Interpretación                                       | Precauciones / Cómo NO usarla                                              |
| -------------------------- | ---------------------------------------------------- | -------------------------------------------------------------------------- |
| **Velocity**               | Número de historias o puntos completados por Sprint. | NO usar para presionar al equipo; es una guía para planificación.          |
| **Burndown**               | Gráfico que muestra trabajo restante vs tiempo.      | NO usar solo para “castigar” retrasos; sirve para ajustar planificación.   |
| **Work in Progress (WIP)** | Cantidad de tareas en ejecución simultáneamente.     | NO sobrecargar al equipo; ayuda a priorizar y detectar cuellos de botella. |

> Esta estructura asegura que Scrum funcione de forma transparente, iterativa y flexible, promoviendo entrega continua, colaboración constante y mejora del equipo.

---

## 🗂️ KANBAN

### 🌟 Introducción y origen

Kanban es una **metodología ágil y ligera** para gestionar el trabajo, enfocada en **visualizar el flujo de tareas y mejorar la eficiencia del proceso**.  

📌 El término proviene del japonés:  
- *kan* ➝ “visual”  
- *ban* ➝ “tarjeta”  

Se desarrolló en **Toyota (~1940)** dentro del sistema *Just in Time (JIT)*, para reducir desperdicios en producción. En 2004, **David Anderson** lo adaptó al **desarrollo de software**, aplicando sus principios a la gestión de tareas en equipos de TI.

A diferencia de Scrum, Kanban no requiere Sprints ni roles fijos, sino que se centra en gestionar el flujo de trabajo existente y adaptarse continuamente a la demanda y prioridades del equipo.

---

### ⚙️ Principios y prácticas básicas de Kanban

1. 🔎 **Visualización del flujo de trabajo**  

- Todas las tareas y etapas se representan en un tablero Kanban con tarjetas.

- Esto permite ver qué se está haciendo, qué está pendiente y qué se ha completado, promoviendo transparencia y comunicación.

2. ⏳ **Límites de trabajo en curso (WIP)**

- Cada columna del tablero tiene un límite máximo de tareas que pueden estar en progreso.

- Esto evita sobrecarga, cuellos de botella y mejora el enfoque del equipo.

- Ejemplo: si “En Progreso” tiene límite 3, el equipo no puede iniciar una cuarta tarea hasta que una anterior avance o termine.

3. 🔄 **Gestión del flujo y mejora evolutiva**  

- Se observa el tiempo que tarda cada tarea en completarse (Lead Time y Cycle Time).

- Se identifican obstáculos, retrasos o bloqueos y se ajusta el proceso para optimizar el flujo.

- Promueve la mejora continua (Kaizen) sin cambiar la estructura de todo el equipo.

4. **📜 Políticas explícitas**

- Se documentan reglas claras sobre cómo se mueve una tarjeta entre columnas.

- Ejemplo: “Una tarea solo puede pasar a ‘Ready for Review’ si ha pasado pruebas unitarias.”

- Ayuda a evitar confusión y asegurar consistencia.

5. **🔁 Bucles de retroalimentación**

- Reuniones periódicas (similares a Retrospective) permiten ajustar el proceso y mejorar la eficiencia.

- No hay Sprints estrictos; la mejora es evolutiva y continua.
---
### 🗂️ Tablero Kanban sugerido para un equipo de desarrollo

Un tablero Kanban típico puede tener las siguientes columnas:

| Columna     | Descripción                             | Límite WIP sugerido   |
| ----------- | --------------------------------------- | --------------------- |
| Backlog     | Tareas pendientes de priorizar          | ∞ (sin límite)        |
| To Do       | Tareas listas para comenzar             | 3–5                   |
| In Progress | Tareas que el equipo está desarrollando | 2–4 por desarrollador |
| Code Review | Tareas en revisión de código            | 2–3                   |
| Testing     | Tareas en pruebas                       | 2–3                   |
| Done        | Tareas completadas y verificadas        | ∞                     |

> El límite WIP depende del tamaño del equipo y complejidad de las tareas. Ajustarlo permite mejorar el flujo y reducir bloqueos.

---

### 📊 Métricas de flujo en Kanban

1. Lead Time → Tiempo total desde que se crea una tarea hasta que se entrega.

  - Indica eficiencia general del flujo.

2. Cycle Time → Tiempo desde que se inicia el trabajo en una tarea hasta que se termina.

  - Útil para identificar retrasos internos o cuellos de botella.

3. Throughput → Número de tareas completadas en un periodo determinado.

  - Permite medir productividad del equipo.

4. Diagrama de flujo acumulado (Cumulative Flow Diagram)

  - Visualiza tareas en cada columna a lo largo del tiempo.

  - Línea estable = flujo estable; líneas que crecen demasiado = cuellos de botella.

---

### 📜 Políticas y clases de servicio

- Políticas: reglas explícitas para mover tareas (ej. revisar código antes de pasar a Testing).

- Clases de servicio: priorización de tareas según urgencia, riesgo o valor de negocio.

  - Ejemplo: “Expedite” → alta prioridad, debe pasar primero; “Standard” → prioridad normal.

- Esto permite gestionar diferentes tipos de trabajo sin interrumpir el flujo general.

### 🔹 Cuándo usar Kanban

Kanban es ideal cuando:

- El trabajo es alto en variabilidad y llega en tickets o solicitudes continuas.

- Se quiere mejorar flujo y visibilidad sin cambiar roles o estructura.

- Se necesita flexibilidad para incorporar cambios sin reiniciar ciclos de Sprint.

- Hay interés en optimizar eficiencia y reducir cuellos de botella, más que planificar iteraciones estrictas.
---
## 🤔 DESIGN THINKING

<div style="text-align: center;"> <img src="https://cdn.dribbble.com/userupload/25408394/file/original-056d431ec68720c851f9e39dd53dab9e.gif" alt="Design Thinking" width="250"> </div> <br>

**Design Thinking (DT)**, o Pensamiento de Diseño, es una **metodología ágil centrada en la innovación** que ayuda a resolver problemas complejos aplicando el pensamiento de los diseñadores.  

Se basa en **tres pilares fundamentales**:  
- **Empatía:** entender profundamente al usuario.  
- **Colaboración:** trabajar eficazmente en equipo.  
- **Experimentación:** crear prototipos, probarlos y recibir feedback.  

El DT busca que una solución de software sea:  
1. **Deseable:** satisface necesidades reales de las personas.  
2. **Técnicamente factible:** posible de construir con la tecnología disponible.  
3. **Económicamente viable:** rentable para el negocio.  

---

### 🛠️ Fases del Design Thinking

<br>

| Fase       | Objetivo Principal | Técnicas Sugeridas | Entregables Mínimos |
|------------|-----------------|-----------------|------------------|
| **Empatizar** | Comprender las necesidades y problemas del usuario. | Observación directa, entrevistas, preguntas “por qué” repetidas, conversaciones profundas. | Notas de campo, grabaciones, mapa de empatía. |
| **Definir** | Enfocar el problema y enmarcar la necesidad clave. | Reuniones de síntesis, análisis de insights. | Declaración de Problema (Problem Statement). |
| **Idear** | Generar muchas posibles soluciones al problema. | Brainstorming, escenarios, mapas mentales. | Ideas conceptuales, casos de uso, priorización de soluciones. |
| **Prototipar** | Representar de forma tangible las ideas seleccionadas. | Bocetos, maquetas de papel, interfaces simples. | Prototipos de baja fidelidad, esquemas funcionales. |
| **Testear** | Evaluar los prototipos con usuarios y aprender del feedback. | Pruebas de aceptación, micro-tests, retroalimentación de usuarios. | Notas de feedback, mejoras o ajustes para iteraciones siguientes. |

---

### 📝 Mini-Caso Práctico

**Problema:** Los estudiantes pierden tiempo porque el sistema de reservas es manual.  

| Fase       | Actividad | Prototipo de Baja Fidelidad |
|------------|----------|----------------------------|
| **Empatizar** | Entrevistas a estudiantes y observación del proceso de reserva. | Nota: “Los estudiantes necesitan saber disponibilidad al instante desde su teléfono”. |
| **Definir** | Identificar problema clave: falta de acceso remoto. | Declaración del Problema: “¿Cómo permitir reservas desde cualquier lugar para reducir tiempo de espera?”. |
| **Idear** | Brainstorming: app móvil, chatbot, kiosco físico. | Idea seleccionada: “Aplicación móvil de reserva rápida”. |
| **Prototipar** | Boceto de interfaz móvil en papel. | Pantalla 1: catálogo de equipos (disponibilidad rojo/verde). Pantalla 2: formulario de reserva. |
| **Testear** | Presentación del boceto a usuarios y recolección de feedback. | Notas sobre mejoras necesarias (ej. disponibilidad detallada). |

---

### 🔄 Relación con SDLC y Metodologías Ágiles

**Reducción de riesgos:**  
- Evita construir lo incorrecto.  
- Validación temprana con usuarios asegura que el producto final aporte valor real.  

**Integración con Scrum:**  
- DT se usa antes o al inicio de Scrum para definir visión del producto y Product Backlog.  
- Garantiza que se construya lo correcto antes de iniciar Sprints.  

**Integración con Kanban:**  
- Las tareas generadas por DT (investigación, diseño conceptual) se pueden colocar en el tablero Kanban.  
- Mejora el flujo de valor y la colaboración del equipo al inicio del proceso.

---

### ⚖️ Cuándo Elegir Cada Metodología Ágil

Cada marco ágil tiene fortalezas particulares según el tipo de proyecto y equipo:

| Metodología       | Cuándo Elegirla |
|------------------|----------------|
| **Scrum**        | - Proyectos con requerimientos cambiantes pero con entregables definidos.<br>- Equipos que necesitan iteraciones cortas y feedback frecuente.<br>- Cuando se requiere coordinación de roles y planificación estructurada por Sprints. |
| **Kanban**       | - Proyectos con flujo de trabajo continuo y alta variabilidad de tareas.<br>- Equipos que manejan tickets, soporte o mantenimiento.<br>- Cuando se busca visualización constante y optimización del flujo sin ciclos fijos. |
| **Design Thinking** | - Cuando se busca innovación o solución de problemas complejos.<br>- Proyectos donde es crítico entender profundamente al usuario.<br>- Antes de iniciar Scrum o Kanban para definir correctamente qué construir. |

---

### ✅ Ventajas y Riesgos de las Metodologías Ágiles

| Metodología       | Beneficios Clave | Limitaciones / Riesgos | Trade-offs Típicos |
|------------------|-----------------|----------------------|-----------------|
| **Scrum**        | - Entregas frecuentes y medibles.<br>- Roles y responsabilidades claras.<br>- Fomenta mejora continua y retroalimentación. | - Rigidez en roles y ceremonias.<br>- Puede ser complicado si los requisitos cambian demasiado rápido.<br>- Riesgo de sobrecarga en Sprints mal planificados. | - Estructura vs flexibilidad.<br>- Planeación inicial más detallada. |
| **Kanban**       | - Flujo continuo y visualización clara.<br>- Flexible ante cambios.<br>- Optimiza tiempo de ciclo y entrega. | - Puede carecer de cadencia fija.<br>- Riesgo de trabajo acumulado si no se controlan límites WIP.<br>- Menos orientación a roles definidos. | - Flexibilidad vs control estructurado.<br>- Menor previsibilidad de entregas. |
| **Design Thinking** | - Fomenta innovación y soluciones centradas en usuario.<br>- Reduce riesgo de construir productos incorrectos.<br>- Iterativo y adaptable. | - No proporciona guía para implementación ni gestión de proyecto.<br>- Requiere tiempo para empatizar y prototipar.<br>- Puede ser percibido como “demorado” en entornos ágiles puros. | - Exploración profunda vs velocidad de ejecución.<br>- Creatividad vs eficiencia. |

---

## 🔚 Conclusiones

Las metodologías ágiles —Scrum, Kanban y Design Thinking— no solo son marcos de trabajo, sino también filosofías que priorizan la **colaboración, la entrega continua de valor y la adaptación al cambio**.  

En un **contexto académico**, permiten:

- Gestionar proyectos de desarrollo de software o trabajos en equipo de forma más organizada.  
- Recibir retroalimentación temprana de profesores o compañeros, evitando invertir tiempo en soluciones incorrectas.  
- Experimentar con prototipos y ajustar ideas antes de entregar la versión final.

En un **contexto profesional**, ayudan a:

- Manejar proyectos complejos con requerimientos cambiantes sin perder eficiencia.  
- Mejorar la comunicación entre diferentes roles dentro de un equipo multidisciplinario.  
- Aumentar la satisfacción del cliente o usuario final al entregar software útil y alineado a sus necesidades.  

> En resumen, integrar estas metodologías en la práctica diaria fomenta un aprendizaje activo, reduce riesgos y potencia la creatividad y productividad tanto en entornos académicos como profesionales.

---

## 📚 Referencias

1. [Asana – Agile Methodology](https://asana.com/es/resources/agile-methodology)  
2. [Atlassian – Agile](https://www.atlassian.com/es/agile)  
3. [AWS – ¿Qué es Scrum?](https://www.aws.amazon.com/es/what-is/scrum/#:~:text=Scrum%20es%20un%20marco%20de,de%20forma%20rentable%20y%20sostenible.)  
4. [Hotjar – Design Thinking y Ágil](https://www.hotjar.com/design-thinking/agile/)  
5. [Asana – What is Kanban](https://asana.com/es/resources/what-is-kanban) 
