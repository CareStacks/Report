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
| *(Foto)* | Salcedo Champi, Matias Rodolfo | u202319698 | Ingeniería de Software | Soy un estudiante de Ingeniería de Software con experiencia en el desarrollo de aplicaciones móviles y web. He participado en proyectos de investigación y desarrollo, y tengo conocimientos en tecnologías como Flutter, Dart, Node.js, Express.js, MongoDB, PostgreSQL, Git, GitHub, entre otras. |
| *(Foto)* | Santillan Alvarado, Melina Liz | U202216058 | Ingeniería de Software | Estudiante de Ingeniería de Software en la UPC. Cuenta con habilidades organizativas, análisis de requerimientos y proactividad para garantizar el correcto desarrollo del proyecto y el cumplimiento de los procesos ágiles. |
| <img src="assets/christofer.jpg" width="100" /> | Costa Morales, Christofer William | u202315968 | Ingeniería de Software | Estudiante de Ingeniería de Software de la UPC. Posee experiencia con los lenguajes de programación: C++, Python, JavaScript, HTML y CSS. En lo personal, capacitado para ayudar y contribuir activamente en el desarrollo técnico de este equipo. |
| <img src="assets/javier.jpg" width="100" /> | Nikaido Vargas, Javier Masaru | U20221G099 | Ingeniería de Software | Estudiante del séptimo ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Contribuirá al equipo aportando en el desarrollo estructural y la validación funcional de la solución propuesta. |
| *(Foto)* | Osores Marchese, Pietro | U202310971 | Ingeniería de Software | Estudiante de Ingeniería de Software en la UPC. Apoyará en las etapas de codificación y trabajo colaborativo, enfocándose en la experiencia de usuario y garantizando entregas de valor dentro de los plazos establecidos por el equipo. |

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
