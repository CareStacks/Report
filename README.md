<div align="center">

### Logo de Universidad

**Universida Peruana de Ciencias Aplicadas**  

**Ingeniería de Software**  

**2026-01**  
<br>

**1ACC0238 - Aplicaciones para Dispositivos Móviles**  
<br>

**NRC:** 3690

**Docente:** Mayta Guillermo, Jorge Luis
<br>

### Informe de Trabajo Final
<br>

**Startup:** CareStacks

**Producto:** CareConnect
<br>

<table>
  <tr>
    <th>Integrante</th>
    <th>Código</th>
  </tr>
  <tr>
    <td>Salcedo Champi, Matias Rodolfo</td>
    <td>U202319698</td>
  </tr>
  <tr>
    <td>Costa Morales, Christofer William</td>
    <td>U202315968</td>
  </tr>
  <tr>
    <td>Nikaido Vargas, Javier Masaru</td>
    <td>U20221G099</td>
  </tr>
  <tr>
    <td>Osores Marchese, Pietro</td>
    <td>U202310971</td>
  </tr>
  <tr>
    <td>Santillan Alvarado, Melina Liz</td>
    <td>U202216058</td>
  </tr>
</table>
<br>

**Abril del 2026**  

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---|---|---|---|
| 1 | 21/04/2026 | Salcedo Champi, Matias Rodolfo; Santillan Alvarado, Melina Liz; Costa Morales, Christofer William; Nikaido Vargas, Javier Masaru; Osores Marchese, Pietro | Avance 1: En esta primera entrega se avanzó con el capítulo 1, 2 y 3 de forma organizada para empezar con el proyecto de CareStacks, estableciendo la idea, un estudio del contexto y las features, respectivamente. |

---

# Project Report Collaboration Insights

---

# Contenido

## Capítulo I: Presentación
- [1.1. Startup Profile](#11-startup-profile)  
  - [1.1.1. Descripción de la Startup](#111-descripcion-de-la-startup)  
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  
- [1.2. Solution Profile](#12-solution-profile)  
  - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problematica)  
  - [1.2.2. Lean UX Process](#122-lean-ux-process)  
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)  
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)  
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)  
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)  

## Capítulo II: Requirements Development and Software Solution Design
- [2.1. Competidores](#21-competidores)  
  - [2.1.1. Análisis competitivo](#211-analisis-competitivo)  
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tacticas-frente-a-competidores)  

- [2.2. Entrevistas](#22-entrevistas)  
  - [2.2.1. Diseño de entrevistas](#221-diseno-de-entrevistas)  
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
  - [2.2.3. Análisis de entrevistas](#223-analisis-de-entrevistas)  

- [2.3. Needfinding](#23-needfinding)  
  - [2.3.1. User Personas](#231-user-personas)  
  - [2.3.2. User Task Matrix](#232-user-task-matrix)  
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)  
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)  
  - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)  

- [2.4. Requirements specification](#24-requirements-specification)  
  - [2.4.1. User Stories](#241-user-stories)  
  - [2.4.2. Impact Mapping](#242-impact-mapping)  
  - [2.4.3. Product Backlog](#243-product-backlog)  

- [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)  
  - [2.5.1. EventStorming](#251-eventstorming)  
    - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)  
    - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)  
    - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)  
  - [2.5.2. Context Mapping](#252-context-mapping)  
  - [2.5.3. Software Architecture](#253-software-architecture)  
    - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)  
    - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)  
    - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)  

- [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)  
  - [2.6.x. Bounded Context](#26x-bounded-context)  
    - [2.6.x.1. Domain Layer](#26x1-domain-layer)  
    - [2.6.x.2. Interface Layer](#26x2-interface-layer)  
    - [2.6.x.3. Application Layer](#26x3-application-layer)  
    - [2.6.x.4. Infrastructure Layer](#26x4-infrastructure-layer)  
    - [2.6.x.5. Bounded Context Software Architecture Component Level Diagrams](#26x5-component-level-diagrams)  
    - [2.6.x.6. Bounded Context Software Architecture Code Level Diagrams](#26x6-code-level-diagrams)  
      - [2.6.x.6.1. Bounded Context Domain Layer Class Diagrams](#26x61-domain-layer-class-diagrams)  
      - [2.6.x.6.2. Bounded Context Database Design Diagram](#26x62-database-design-diagram)  

## Capítulo III: Solution UI/UX Design
- [3.1. Product design](#31-product-design)  
  - [3.1.1. Style Guidelines](#311-style-guidelines)  
    - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)  
  - [3.1.2. Information Architecture](#312-information-architecture)  
    - [3.1.2.1. Organization Systems](#3121-organization-systems)  
    - [3.1.2.2. Labelling Systems](#3122-labelling-systems)  
    - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)  
    - [3.1.2.4. Searching Systems](#3124-searching-systems)  
    - [3.1.2.5. Navigation Systems](#3125-navigation-systems)  
  - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)  
    - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)  
    - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)  
  - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)  
    - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)  
    - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)  
    - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)  
    - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)  
    - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)  

## Capítulo IV: Product Implementation & Validation
- [4.1. Product Implementation & Validation](#41-product-implementation--validation)  
  - [4.1.1. Software Configuration Management](#411-software-configuration-management)  
    - [4.1.1.1. Software Development Environment Configuration](#4111-software-development-environment-configuration)  
    - [4.1.1.2. Source Code Management](#4112-source-code-management)  
    - [4.1.1.3. Source Code Style Guide & Conventions](#4113-source-code-style-guide--conventions)  
    - [4.1.1.4. Software Deployment Configuration](#4114-software-deployment-configuration)  

- [4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)  
  - [4.2.1. Sprint n](#421-sprint-n)  
    - [4.2.1.1. Sprint Planning n](#4211-sprint-planning-n)  
    - [4.2.1.2. Sprint Backlog n](#4212-sprint-backlog-n)  
    - [4.2.1.3. Development Evidence for Sprint Review](#4213-development-evidence)  
    - [4.2.1.4. Testing Suite Evidence for Sprint Review](#4214-testing-suite-evidence)  
    - [4.2.1.5. Execution Evidence for Sprint Review](#4215-execution-evidence)  
    - [4.2.1.6. Services Documentation Evidence for Sprint Review](#4216-services-documentation-evidence)  
    - [4.2.1.7. Software Deployment Evidence for Sprint Review](#4217-software-deployment-evidence)  
    - [4.2.1.8. Team Collaboration Insights during Sprint](#4218-team-collaboration-insights)  

- [4.3. Validation Interviews](#43-validation-interviews)  
  - [4.3.1. Diseño de Entrevistas](#431-diseno-de-entrevistas)  
  - [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)  
  - [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-segun-heuristicas)  

## [Conclusiones](#conclusiones)  
## [Glosario](#glosario)  
## [Bibliografía](#bibliografia)  
## [Anexos](#anexos)  

---


# Student Outcome

El curso de Aplicaciones para Dispositivos Móviles contribuye al cumplimiento del Student Outcome ABET:

**ABET - EAC - Student Outcome 7**

**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

A continuación se describe las acciones realizadas y conclusiones del grupo que sustentan el logro del ABET – EAC - Student Outcome 7.

| Criterio específico | Acciones realizadas | Conclusiones |
|---|---|---|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | En el marco del proyecto CareConnect, el equipo tuvo que ponerse al día con varias tecnologías que no habíamos trabajado antes con ese nivel de profundidad: desarrollo móvil multiplataforma con Flutter, integración con servicios RESTful propios y de terceros, y los principios de Domain-Driven Design. Cada integrante investigó por su cuenta y también en conjunto, según las necesidades técnicas que iban surgiendo. | Aprender tecnologías nuevas mientras se construye algo real fue exigente, pero también fue lo que permitió que el proyecto avanzara. Quedó claro que la capacidad de investigar y aplicar lo aprendido rápidamente es tan importante como el conocimiento previo. |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software. | Detectamos vacíos concretos en temas como arquitectura orientada a dominios (DDD), diseño UX/UI pensado para aplicaciones de salud, y las normas vinculadas a la privacidad de datos de pacientes. Para cerrar esas brechas recurrimos a documentación oficial, bibliografía especializada y recursos en línea. | Este proyecto dejó en evidencia que el campo del software no se detiene: lo que hoy es estándar, mañana puede estar desactualizado. Adaptarse y seguir aprendiendo no es una opción, es parte del trabajo de cualquier ingeniero de software. |

---

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**CareStacks** es una startup de tecnología orientada al sector salud y bienestar social, fundada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC). El proyecto nació de una necesidad concreta: los cuidadores y pacientes geriátricos no cuentan con herramientas digitales realmente pensadas para organizar el cuidado diario, dar seguimiento a tratamientos y mantener una comunicación clara entre todos los involucrados. CareStacks busca cubrir esa brecha con una solución práctica y accesible.

**Misión:** Brindar a cuidadores y pacientes geriátricos una herramienta móvil accesible que facilite el seguimiento del bienestar del paciente y mejore la coordinación de las actividades de cuidado.

**Visión:** Consolidarse como la plataforma de referencia en Latinoamérica para la gestión del cuidado geriátrico, apostando por soluciones tecnológicas que pongan a las personas en el centro.

**Producto:** **CareConnect** es una aplicación móvil nativa y multiplataforma pensada para el día a día del cuidado: monitoreo de rutinas, gestión de tratamientos y comunicación entre cuidadores. Sus funcionalidades principales incluyen:

1. Calendario de medicación y terapias programadas.
2. Alertas y recordatorios en tiempo real.
3. Carpeta digital para documentos clínicos y tratamientos.
4. Historial de notas y registro de evolución del paciente.
5. Compartición de perfiles entre cuidadores para garantizar continuidad en la atención.

### 1.1.2. Perfiles de integrantes del equipo

> *Nota: Los perfiles de cada integrante del equipo serán completados por el responsable de cada sección correspondiente, incluyendo foto, nombres y apellidos, código de estudiante, carrera y párrafo de resumen de conocimientos técnicos y habilidades.*

| Foto | Integrante | Código | Carrera | Resumen |
|---|---|---|---|---|
| <img src="assets/matias.jpg" width="100" /> | Salcedo Champi, Matias Rodolfo | u202319698 | Ingeniería de Software | Soy un estudiante de Ingeniería de Software con experiencia en el desarrollo de aplicaciones móviles y web. He participado en proyectos de investigación y desarrollo, y tengo conocimientos en tecnologías como Flutter, Dart, Node.js, Express.js, MongoDB, PostgreSQL, Git, GitHub, entre otras. |
| <img src="assets/melina.jpg" width="100" /> | Santillan Alvarado, Melina Liz | U202216058 | Ingeniería de Software | Estudiante de Ingeniería de Software en la UPC. Cuenta con habilidades organizativas, análisis de requerimientos y proactividad para garantizar el correcto desarrollo del proyecto y el cumplimiento de los procesos ágiles. |
| <img src="assets/christofer.jpg" width="100" /> | Costa Morales, Christofer William | u202315968 | Ingeniería de Software | Estudiante de Ingeniería de Software de la UPC. Posee experiencia con los lenguajes de programación: C++, Python, JavaScript, HTML y CSS. En lo personal, capacitado para ayudar y contribuir activamente en el desarrollo técnico de este equipo. |
| <img src="assets/javier.jpg" width="100" /> | Nikaido Vargas, Javier Masaru | U20221G099 | Ingeniería de Software | Estudiante del séptimo ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Contribuirá al equipo aportando en el desarrollo estructural y la validación funcional de la solución propuesta. |
| <img src="assets/pietro.jpg" width="100" /> | Osores Marchese, Pietro | U202310971 | Ingeniería de Software | Estudiante de Ingeniería de Software en la UPC. Apoyará en las etapas de codificación y trabajo colaborativo, enfocándose en la experiencia de usuario y garantizando entregas de valor dentro de los plazos establecidos por el equipo. |

---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y Problemática

#### Antecedentes

En el Perú, el crecimiento de la población adulta mayor ha hecho más visible la necesidad de soluciones que permitan organizar mejor el cuidado geriátrico, tanto en casa como en entornos de atención especializada. Muchos pacientes geriátricos requieren seguimiento continuo de medicación, citas médicas, signos de alerta y rutinas de apoyo diario, pero ese control todavía suele manejarse de forma manual, fragmentada y dependiente de la memoria de los cuidadores.

A nivel práctico, esta situación genera desgaste en los cuidadores y reduce la autonomía de los propios pacientes geriátricos, quienes muchas veces dependen de terceros para recordar tratamientos, registrar síntomas o informar cambios en su estado. Aunque existen herramientas orientadas a clínicas y hospitales, todavía falta una solución centrada en el cuidado cotidiano, domiciliario y compartido que caracteriza a este segmento.

#### Problemática — Técnica The 5W's y 2H's

**Who (¿Quiénes?):**
Los más afectados son los cuidadores formales e informales y los pacientes geriátricos que dependen de una rutina de atención constante. Ambos segmentos viven de forma directa las consecuencias de una mala coordinación, ya sea por sobrecarga en el cuidado o por falta de seguimiento oportuno.

**What (¿Qué?):**
No existe una plataforma que centralice de forma práctica los tratamientos, rutinas, recordatorios, documentos clínicos e historial de evolución de un paciente geriátrico. Esa ausencia hace que coordinarse entre varios cuidadores sea difícil y que el propio paciente tenga poca visibilidad de su proceso de cuidado.

**Where (¿Dónde?):**
El problema ocurre principalmente en entornos de cuidado domiciliario, comunitario y de atención particular en el Perú, aunque la situación es comparable en otros países de Latinoamérica, donde gran parte del cuidado geriátrico también recae en las familias y cuidadores externos.

**When (¿Cuándo?):**
No es algo que pase de vez en cuando. Se presenta todos los días: al coordinar la medicación, al hacer el cambio de turno entre cuidadores, al buscar el historial clínico o al intentar registrar si el paciente mejoró o empeoró.

**Why (¿Por qué?):**
El cuidado geriátrico involucra a varios actores —paciente, familiares, enfermeros, médicos y cuidadores contratados—, pero no hay herramientas móviles accesibles que conecten esa información y la mantengan actualizada. El resultado es que muchas decisiones se toman con datos incompletos o tardíos, lo que incrementa el riesgo para el paciente.

**How (¿Cómo?):**
Se traduce en situaciones concretas: medicamentos olvidados o duplicados, citas médicas mal registradas, signos de alerta que no se comunican a tiempo, documentos clínicos dispersos y una dependencia excesiva de llamadas o mensajes informales para coordinar el cuidado.

**How Much (¿Cuánto?):**
El impacto se refleja en tiempo perdido, errores evitables en la administración del cuidado, mayor carga física y emocional para los cuidadores, y un seguimiento menos seguro para los pacientes geriátricos. Cuando no existe una herramienta común de coordinación, aumentan los costos asociados a consultas repetidas, omisiones en tratamientos y desorganización en la atención diaria.

---

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1 — Cuidadores de pacientes geriátricos:**

Hoy los cuidadores de pacientes geriátricos gestionan rutinas complejas de medicación, controles, citas y seguimiento médico con lo que tienen a la mano: libretas, grupos de WhatsApp, hojas de cálculo o recordatorios dispersos. Son herramientas útiles, pero no fueron diseñadas para un entorno donde la continuidad y la precisión importan tanto.

Lo que identificamos como el punto más crítico es la falta de una plataforma que les permita sincronizar información con otros cuidadores, acceder rápido al historial del paciente y recibir alertas a tiempo sin aumentar su carga operativa.

¿Cómo podríamos diseñar una solución móvil que centralice la gestión del cuidado geriátrico, facilite la comunicación entre cuidadores y reduzca los riesgos que genera la descoordinación diaria?

**Problem Statement 2 — Pacientes geriátricos:**

Los pacientes geriátricos suelen enfrentar dificultades para seguir sus tratamientos, recordar indicaciones médicas y mantener organizada su información de salud, especialmente cuando dependen de apoyo parcial o alternado de distintos cuidadores.

Lo que falta es una herramienta simple que les permita visualizar sus rutinas, entender qué actividades tienen pendientes y registrar cómo se sienten, sin depender por completo de llamadas, papeles o recordatorios aislados.

¿Cómo podríamos darle al paciente geriátrico mayor visibilidad y participación en su propio cuidado mediante una herramienta simple, clara y fácil de usar?

---

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. Creemos que hay demanda real de aplicaciones móviles especializadas en la gestión del cuidado geriátrico en Perú y Latinoamérica.
2. Creemos que los cuidadores adoptarán herramientas digitales si son fáciles de configurar y no exigen formación técnica previa.
3. Creemos que un modelo freemium permitirá llegar tanto a usuarios individuales como a instituciones de salud, capturando distintos perfiles de uso.
4. Creemos que la descoordinación entre cuidadores genera costos concretos y evitables que justifican adoptar una solución como la nuestra.

**User Assumptions:**

1. **¿Quién es el usuario?** Cuidadores formales e informales de pacientes geriátricos, y pacientes geriátricos con capacidad de participar activamente en el seguimiento de su cuidado.
2. **¿Dónde encaja en su vida?** En la rutina diaria de cuidado: cuando se administran medicamentos, se revisan citas, se registran observaciones o se consulta el historial del paciente.
3. **¿Qué problema resuelve?** La descoordinación, la pérdida de información y la baja visibilidad del estado del tratamiento y las actividades pendientes.
4. **¿Cuándo y cómo se usa?** Desde el celular, varias veces al día: al iniciar una jornada de cuidado, al cumplir una indicación médica, al reportar cambios y al revisar recordatorios.
5. **¿Qué características importan más?** Las alertas de medicación, el calendario de controles, las notas de evolución, la compartición de perfiles y el acceso rápido a información clínica relevante.
6. **¿Cómo debe verse?** Simple, claro y confiable, con una interfaz fácil de entender tanto para cuidadores con poco tiempo como para pacientes mayores que requieren flujos directos.

---

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis 1:**

Creemos que los cuidadores podrán gestionar los tratamientos de sus pacientes de forma más segura y coordinada **si** ofrecemos un calendario integrado de medicación y controles con alertas en tiempo real **para** cuidadores formales e informales de pacientes geriátricos.

**Sabremos que funciona cuando** el 70% de los usuarios activos utilice la función de alertas de medicación al menos una vez por día durante las primeras cuatro semanas.

---

**Hypothesis 2:**

Creemos que los pacientes geriátricos se sentirán más orientados y participarán mejor en su cuidado **si** tienen acceso claro a sus actividades, recordatorios y registro de evolución **para** pacientes geriátricos con autonomía parcial o acompañada.

**Sabremos que funciona cuando** el 60% de los pacientes activos consulte o confirme al menos una actividad diaria dentro de la plataforma durante el primer mes.

---

**Hypothesis 3:**

Creemos que la transición entre turnos de cuidado será más fluida **si** implementamos una función de compartición de perfiles de pacientes con historial completo **para** cuidadores que se alternan en la atención de un mismo paciente geriátrico.

**Sabremos que funciona cuando** el tiempo promedio de transferencia de información entre cuidadores al cambio de turno baje un 50% respecto al proceso manual, según los registros de actividad de la app.

---

#### 1.2.2.4. Lean UX Canvas

<table>
  <tr>
    <td valign="top" width="33%">
      <b>1. Business Problem</b><br><br>
      Los cuidadores de pacientes geriátricos manejan información crítica de salud de forma desordenada y sin herramientas pensadas para eso, lo que genera riesgos para el paciente y agotamiento en quien cuida.
    </td>
    <td rowspan="2" valign="top" width="33%">
      <b>5. Solution Ideas</b><br><br>
      App móvil multiplataforma con calendario de medicación y terapias, sistema de alertas, carpeta de documentos, historial de evolución y perfiles compartidos.
    </td>
    <td valign="top" width="33%">
      <b>2. Business Outcomes</b><br><br>
      Menos errores de medicación. Mejor coordinación entre cuidadores. Tasas de retención superiores al 60% al tercer mes de uso.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>3. Users & Customers</b><br><br>
      Segmento 1: Cuidadores formales e informales de pacientes geriátricos.<br><br>
      Segmento 2: Pacientes geriátricos que necesitan seguimiento simple y claro de su cuidado diario.
    </td>
    <td valign="top">
      <b>4. User Benefits</b><br><br>
      Gestión centralizada de tratamientos y rutinas. Historial completo siempre disponible. Alertas oportunas y coordinación real con otros cuidadores.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>6. Hypotheses</b><br><br>
      Los cuidadores adoptarán la app si la configuración inicial no les toma más de 10 minutos. Los pacientes geriátricos valorarán una interfaz simple y comprensible. Compartir perfiles mejorará la coordinación entre turnos.
    </td>
    <td valign="top">
      <b>7. What's the most important thing we need to learn first?</b><br><br>
      ¿Los cuidadores están dispuestos a registrar información durante su jornada, o lo perciben como una carga extra?
    </td>
    <td valign="top">
      <b>8. What's the least amount of work we need to do to learn the next most important thing?</b><br><br>
      Entrevistas con al menos 6 cuidadores (3 formales, 3 informales) para entender cómo trabajan hoy y dónde sienten más fricción en la gestión del cuidado.
    </td>
  </tr>
</table>

---

## 1.3. Segmentos Objetivo

CareConnect apunta a dos segmentos bien diferenciados, definidos a partir del análisis del problema y las personas que lo viven de cerca.

---

### Segmento Objetivo 1: Cuidadores de pacientes geriátricos

**Descripción:**
Este segmento incluye tanto a cuidadores formales —enfermeros, técnicos de salud y asistentes geriátricos en atención domiciliaria o centros de cuidado— como a cuidadores informales: familiares que asumen el rol principal en casa, muchas veces sin formación especializada pero con responsabilidad directa sobre la rutina del paciente.

**Características demográficas:**

- **Edad:** 25 a 60 años.
- **Género:** Con presencia mayoritaria de mujeres en labores de cuidado, aunque el segmento no excluye a ningún género.
- **Ubicación:** Principalmente zonas urbanas y periurbanas del Perú, donde existe mayor acceso a smartphones y servicios de atención domiciliaria.
- **Nivel educativo:** Variable: desde secundaria completa hasta educación superior técnica o universitaria en el caso de cuidadores formales.
- **Ocupación:** Cuidador/a formal (con experiencia en atención geriátrica) o cuidador/a informal (familiar responsable del acompañamiento diario).
- **Nivel socioeconómico:** Sectores B, C y D.

**Características conductuales y psicográficas:**

Usan el celular con frecuencia para organizar su vida diaria y muestran disposición a incorporar apps que realmente les faciliten el trabajo. Sin embargo, viven bajo presión constante: deben controlar medicación, citas, cambios de estado y comunicación con otros actores del cuidado. Valoran la simplicidad por encima de todo, porque si una herramienta les toma demasiado tiempo o esfuerzo, dejan de usarla. La mayoría accede desde dispositivos móviles de gama media.

**Datos estadísticos de sustento:**

Se trata de un segmento en crecimiento debido al aumento sostenido de la población adulta mayor y a la alta participación de familiares en tareas de cuidado no remunerado. Su relevancia también se explica por la sobrecarga física y emocional asociada al seguimiento continuo de pacientes con necesidades geriátricas.

---

### Segmento Objetivo 2: Pacientes geriátricos

**Descripción:**
Son adultos mayores que requieren seguimiento frecuente de su estado de salud, medicación y actividades diarias. Algunos conservan autonomía parcial y pueden interactuar por sí mismos con la aplicación; otros necesitan apoyo de un cuidador, pero igualmente se benefician de una herramienta que haga visible su rutina y su progreso.

**Características demográficas:**

- **Edad:** 60 años a más.
- **Género:** Sin predominancia específica.
- **Ubicación:** Principalmente zonas urbanas y periurbanas, donde el acceso a smartphones o apoyo digital es más viable.
- **Nivel educativo:** Variable; desde educación básica hasta educación superior.
- **Condición de uso:** Pacientes con autonomía parcial o acompañada que necesitan recordatorios, seguimiento y visualización simple de su cuidado.
- **Nivel socioeconómico:** Sectores B, C y D.

**Características conductuales y psicográficas:**

Este segmento valora especialmente la claridad, la legibilidad y la simplicidad. Necesita recordatorios visibles, instrucciones fáciles de entender y una experiencia que no genere confusión ni dependencia técnica excesiva. Cuando la información está bien organizada, los pacientes pueden involucrarse mejor en su tratamiento y reducir olvidos o malentendidos sobre su rutina diaria.

**Datos estadísticos de sustento:**

Su relevancia está asociada al envejecimiento de la población y a la necesidad de promover mayor adherencia a tratamientos, monitoreo oportuno y participación del paciente en su propio proceso de cuidado. Es un segmento que requiere soluciones digitales con barreras de uso mínimas y utilidad inmediata.

---

*Referencias*

- Instituto Nacional de Estadística e Informática [INEI]. Información general sobre población adulta mayor y dinámicas de cuidado en el Perú.
- Organización Mundial de la Salud [OMS]. Información general sobre envejecimiento saludable, cuidado de largo plazo y adherencia a tratamientos en personas mayores.

## 2.1. Competidores
### 2.1.1. Análisis competitivo <a id="211-analisis-competitivo"></a>
### 2.1.2. Estrategias y tácticas frente a competidores <a id="212-estrategias-y-tacticas-frente-a-competidores"></a>

## 2.2. Entrevistas <a id="22-entrevistas"></a>
### 2.2.1. Diseño de entrevistas <a id="221-diseno-de-entrevistas"></a>
### 2.2.2. Registro de entrevistas <a id="222-registro-de-entrevistas"></a>
### 2.2.3. Análisis de entrevistas <a id="223-analisis-de-entrevistas"></a>

## 2.3. Needfinding <a id="23-needfinding"></a>
### 2.3.1. User Personas <a id="231-user-personas"></a>
### 2.3.2. User Task Matrix <a id="232-user-task-matrix"></a>
### 2.3.3. User Journey Mapping <a id="233-user-journey-mapping"></a>
### 2.3.4. Empathy Mapping <a id="234-empathy-mapping"></a>
### 2.3.5. Ubiquitous Language <a id="235-ubiquitous-language"></a>

## 2.4. Requirements specification <a id="24-requirements-specification"></a>
### 2.4.1. User Stories <a id="241-user-stories"></a>
### 2.4.2. Impact Mapping <a id="242-impact-mapping"></a>
### 2.4.3. Product Backlog <a id="243-product-backlog"></a>

## 2.5. Strategic-Level Domain-Driven Design <a id="25-strategic-level-domain-driven-design"></a>
### 2.5.1. EventStorming <a id="251-eventstorming"></a>
#### 2.5.1.1. Candidate Context Discovery <a id="2511-candidate-context-discovery"></a>
#### 2.5.1.2. Domain Message Flows Modeling <a id="2512-domain-message-flows-modeling"></a>
#### 2.5.1.3. Bounded Context Canvases <a id="2513-bounded-context-canvases"></a>

### 2.5.2. Context Mapping <a id="252-context-mapping"></a>

### 2.5.3. Software Architecture <a id="253-software-architecture"></a>
#### 2.5.3.1. Software Architecture Context Level Diagrams <a id="2531-software-architecture-context-level-diagrams"></a>
#### 2.5.3.2. Software Architecture Container Level Diagrams <a id="2532-software-architecture-container-level-diagrams"></a>
#### 2.5.3.3. Software Architecture Deployment Diagrams <a id="2533-software-architecture-deployment-diagrams"></a>

## 2.6. Tactical-Level Domain-Driven Design <a id="26-tactical-level-domain-driven-design"></a>
### 2.6.x. Bounded Context <a id="26x-bounded-context"></a>
#### 2.6.x.1. Domain Layer <a id="26x1-domain-layer"></a>
#### 2.6.x.2. Interface Layer <a id="26x2-interface-layer"></a>
#### 2.6.x.3. Application Layer <a id="26x3-application-layer"></a>
#### 2.6.x.4. Infrastructure Layer <a id="26x4-infrastructure-layer"></a>
#### 2.6.x.5. Bounded Context Software Architecture Component Level Diagrams <a id="26x5-component-level-diagrams"></a>
#### 2.6.x.6. Bounded Context Software Architecture Code Level Diagrams <a id="26x6-code-level-diagrams"></a>
##### 2.6.x.6.1. Bounded Context Domain Layer Class Diagrams <a id="26x61-domain-layer-class-diagrams"></a>
##### 2.6.x.6.2. Bounded Context Database Design Diagram <a id="26x62-database-design-diagram"></a>

---

# Capítulo III: Solution UI/UX Design

## 3.1. Product design <a id="31-product-design"></a>

### 3.1.1. Style Guidelines <a id="311-style-guidelines"></a>
#### 3.1.1.1. General Style Guidelines <a id="3111-general-style-guidelines"></a>

### 3.1.2. Information Architecture <a id="312-information-architecture"></a>
#### 3.1.2.1. Organization Systems <a id="3121-organization-systems"></a>
#### 3.1.2.2. Labelling Systems <a id="3122-labelling-systems"></a>
#### 3.1.2.3. SEO Tags and Meta Tags <a id="3123-seo-tags-and-meta-tags"></a>
#### 3.1.2.4. Searching Systems <a id="3124-searching-systems"></a>
#### 3.1.2.5. Navigation Systems <a id="3125-navigation-systems"></a>

### 3.1.3. Landing Page UI Design <a id="313-landing-page-ui-design"></a>
#### 3.1.3.1. Landing Page Wireframe <a id="3131-landing-page-wireframe"></a>
#### 3.1.3.2. Landing Page Mock-up <a id="3132-landing-page-mock-up"></a>

### 3.1.4. Mobile Applications UX/UI Design <a id="314-mobile-applications-uxui-design"></a>
#### 3.1.4.1. Mobile Applications Wireframes <a id="3141-mobile-applications-wireframes"></a>
#### 3.1.4.2. Mobile Applications Wireflow Diagrams <a id="3142-mobile-applications-wireflow-diagrams"></a>
#### 3.1.4.3. Mobile Applications Mock-ups <a id="3143-mobile-applications-mock-ups"></a>
#### 3.1.4.4. Mobile Applications User Flow Diagrams <a id="3144-mobile-applications-user-flow-diagrams"></a>
#### 3.1.4.5. Mobile Applications Prototyping <a id="3145-mobile-applications-prototyping"></a>

---

# Capítulo IV: Product Implementation & Validation

## 4.1. Product Implementation & Validation <a id="41-product-implementation--validation"></a>

### 4.1.1. Software Configuration Management <a id="411-software-configuration-management"></a>
#### 4.1.1.1. Software Development Environment Configuration <a id="4111-software-development-environment-configuration"></a>
#### 4.1.1.2. Source Code Management <a id="4112-source-code-management"></a>
#### 4.1.1.3. Source Code Style Guide & Conventions <a id="4113-source-code-style-guide--conventions"></a>
#### 4.1.1.4. Software Deployment Configuration <a id="4114-software-deployment-configuration"></a>

## 4.2. Landing Page & Mobile Application Implementation <a id="42-landing-page--mobile-application-implementation"></a>

### 4.2.1. Sprint n <a id="421-sprint-n"></a>
#### 4.2.1.1. Sprint Planning n <a id="4211-sprint-planning-n"></a>
#### 4.2.1.2. Sprint Backlog n <a id="4212-sprint-backlog-n"></a>
#### 4.2.1.3. Development Evidence for Sprint Review <a id="4213-development-evidence"></a>
#### 4.2.1.4. Testing Suite Evidence for Sprint Review <a id="4214-testing-suite-evidence"></a>
#### 4.2.1.5. Execution Evidence for Sprint Review <a id="4215-execution-evidence"></a>
#### 4.2.1.6. Services Documentation Evidence for Sprint Review <a id="4216-services-documentation-evidence"></a>
#### 4.2.1.7. Software Deployment Evidence for Sprint Review <a id="4217-software-deployment-evidence"></a>
#### 4.2.1.8. Team Collaboration Insights during Sprint <a id="4218-team-collaboration-insights"></a>

## 4.3. Validation Interviews <a id="43-validation-interviews"></a>
### 4.3.1. Diseño de Entrevistas <a id="431-diseno-de-entrevistas"></a>
### 4.3.2. Registro de Entrevistas <a id="432-registro-de-entrevistas"></a>
### 4.3.3. Evaluaciones según heurísticas <a id="433-evaluaciones-segun-heuristicas"></a>

---

# Conclusiones <a id="conclusiones"></a>

# Glosario <a id="glosario"></a>

# Bibliografía <a id="bibliografia"></a>

# Anexos <a id="anexos"></a>
