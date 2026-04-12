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

**CareStacks** es una startup de tecnología orientada al sector salud y bienestar social, fundada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC). El proyecto nació de una necesidad concreta: los cuidadores de personas con discapacidades mentales y/o físicas —tanto los profesionales como los familiares que asumen ese rol en casa— no cuentan con herramientas digitales pensadas para su realidad. CareStacks busca cambiar eso.

**Misión:** Brindar a cuidadores y familias una herramienta móvil accesible que facilite el seguimiento del bienestar del paciente y mejore la coordinación entre todos los que participan en su cuidado.

**Visión:** Consolidarse como la plataforma de referencia en Latinoamérica para la gestión del cuidado de personas con discapacidad, apostando por soluciones tecnológicas que pongan a las personas en el centro.

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

En el Perú, según el INEI, más de 3 millones de personas presentan algún tipo de discapacidad, lo que representa alrededor del 10.4% de la población (INEI, 2017). Una parte significativa de ese grupo necesita cuidado permanente, ya sea de familiares o de profesionales de la salud. El problema está en cómo se organiza ese cuidado: en la mayoría de los casos sigue siendo manual, descoordinado y propenso a errores que pueden tener consecuencias directas sobre la salud del paciente.

A nivel global, la OMS advierte que la carga que soportan los cuidadores informales —en su mayoría familiares— es uno de los principales factores detrás del agotamiento y los problemas de salud mental en adultos (OMS, 2021). Las aplicaciones que existen hoy apuntan casi exclusivamente a entornos clínicos institucionales, sin contemplar el cuidado que ocurre en casa o en la comunidad, que es donde se da la mayor parte de la atención.

#### Problemática — Técnica The 5W's y 2H's

**Who (¿Quiénes?):**
Los más afectados son los cuidadores —enfermeros, terapeutas, pero también familiares y voluntarios— de personas con discapacidad. Ellos, junto con las mismas personas bajo cuidado y sus familias, cargan con las consecuencias de una coordinación que muchas veces falla.

**What (¿Qué?):**
No existe una plataforma que centralice de forma práctica los tratamientos, rutinas, documentos clínicos e historial de progreso de una persona con discapacidad. Esa ausencia hace que coordinarse entre varios cuidadores sea difícil y que tomar decisiones con información actualizada sea casi un lujo.

**Where (¿Dónde?):**
El problema ocurre principalmente en entornos de cuidado domiciliario y comunitario en el Perú, aunque la situación es bastante similar en otros países de Latinoamérica, donde los sistemas de salud pública tampoco logran cubrir todas las necesidades de atención de personas con discapacidad.

**When (¿Cuándo?):**
No es algo que pase de vez en cuando. Se presenta todos los días: al coordinar la medicación, al hacer el cambio de turno entre cuidadores, al buscar el historial clínico o al intentar registrar si el paciente mejoró o empeoró.

**Why (¿Por qué?):**
Cuidar a una persona con discapacidad involucra a muchos actores —médicos, terapeutas, familiares, cuidadores contratados— pero no hay herramientas móviles accesibles que los conecten y centralicen la información que todos manejan. El resultado es que las decisiones se toman con datos incompletos o desactualizados, lo que pone en riesgo al paciente.

**How (¿Cómo?):**
Se traduce en situaciones concretas: un medicamento administrado dos veces porque nadie avisó que ya se dio, documentos clínicos perdidos, terapias que se saltan o se repiten, y la imposibilidad de detectar a tiempo si el paciente está mejorando o no.

**How Much (¿Cuánto?):**
La OMS estima que el 15% de la población mundial vive con algún tipo de discapacidad (OMS, 2021). En el Perú, el INEI calcula que más de 1.5 millones de personas actúan como cuidadores principales, muchos de ellos dedicando entre 8 y 12 horas diarias a esa tarea. Los costos de no tener herramientas adecuadas se traducen en errores de medicación, hospitalizaciones que podrían haberse evitado y pérdida de productividad laboral de los cuidadores.

---

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1 — Cuidadores de personas con discapacidad:**

Hoy los cuidadores de personas con discapacidad gestionan rutinas complejas de medicación, terapias y seguimiento médico con lo que tienen a mano: libretas, grupos de WhatsApp, hojas de cálculo. Herramientas que funcionan para otras cosas, pero que no fueron diseñadas para este contexto.

Lo que identificamos como el punto más crítico es la falta de una plataforma que les permita sincronizar información con otros cuidadores, acceder rápido al historial del paciente y recibir alertas a tiempo.

¿Cómo podríamos diseñar una solución móvil que centralice la gestión del cuidado, facilite la comunicación entre cuidadores y reduzca los riesgos que genera la descoordinación?

**Problem Statement 2 — Familiares de personas con discapacidad:**

Los familiares que no ejercen el rol de cuidador principal tienen un problema de visibilidad: cuando su familiar está a cargo de un profesional o en un centro de atención, no saben con claridad qué pasó ese día, qué medicamentos se dieron ni cómo evolucionó.

Lo que falta es un canal estructurado que les permita ver el registro de actividades, tratamientos y evolución del paciente sin tener que llamar o preguntar constantemente.

¿Cómo podríamos darle a las familias acceso real y tranquilizador a la información del cuidado de su familiar, con una herramienta que no requiera conocimientos técnicos?

---

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. Creemos que hay demanda real de aplicaciones móviles especializadas en la gestión del cuidado de personas con discapacidad en Perú y Latinoamérica.
2. Creemos que los cuidadores adoptarán herramientas digitales si son fáciles de configurar y no exigen formación técnica previa.
3. Creemos que un modelo freemium permitirá llegar tanto a usuarios individuales como a instituciones de salud, capturando distintos perfiles de uso.
4. Creemos que la descoordinación entre cuidadores genera costos concretos y evitables que justifican adoptar una solución como la nuestra.

**User Assumptions:**

1. **¿Quién es el usuario?** Cuidadores formales e informales de personas con discapacidad, y familiares que quieren mantenerse informados sobre el estado de su ser querido.
2. **¿Dónde encaja en su vida?** En su rutina de cuidado diaria: cuando dan medicamentos, registran terapias, documentan avances o hacen el cambio de turno con otro cuidador.
3. **¿Qué problema resuelve?** La descoordinación, la pérdida de información y la falta de visibilidad compartida sobre el estado del paciente.
4. **¿Cuándo y cómo se usa?** Desde el celular, varias veces al día: al empezar y terminar un turno, al administrar medicación y al registrar observaciones.
5. **¿Qué características importan más?** Las alertas de medicación, el calendario de terapias, las notas de evolución, la compartición de perfiles y el almacenamiento de documentos clínicos.
6. **¿Cómo debe verse?** Simple, claro y confiable. Pensado para usarse bajo presión, con flujos que no requieran más pasos de los necesarios.

---

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis 1:**

Creemos que los cuidadores podrán gestionar los tratamientos de sus pacientes de forma más segura y coordinada **si** ofrecemos un calendario integrado de medicación y terapias con alertas en tiempo real **para** cuidadores formales e informales de personas con discapacidad.

**Sabremos que funciona cuando** el 70% de los usuarios activos utilice la función de alertas de medicación al menos una vez por día durante las primeras cuatro semanas.

---

**Hypothesis 2:**

Creemos que las familias se sentirán más tranquilas respecto al cuidado de su familiar **si** tienen acceso en tiempo real al historial de actividades, notas de evolución y estado del paciente **para** los familiares de personas bajo cuidado de terceros.

**Sabremos que funciona cuando** el 60% de los perfiles de pacientes tenga al menos un familiar vinculado y activo en la plataforma al finalizar el primer mes.

---

**Hypothesis 3:**

Creemos que la transición entre turnos de cuidado será más fluida **si** implementamos una función de compartición de perfiles de pacientes con historial completo **para** cuidadores que se alternan en la atención de una misma persona.

**Sabremos que funciona cuando** el tiempo promedio de transferencia de información entre cuidadores al cambio de turno baje un 50% respecto al proceso manual, según los registros de actividad de la app.

---

#### 1.2.2.4. Lean UX Canvas

<table>
  <tr>
    <td valign="top" width="33%">
      <b>1. Business Problem</b><br><br>
      Los cuidadores de personas con discapacidad manejan información crítica de salud de forma desordenada y sin herramientas pensadas para eso, lo que genera riesgos para el paciente y agotamiento en quien cuida.
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
      Segmento 1: Cuidadores formales e informales de personas con discapacidad.<br><br>
      Segmento 2: Familiares que quieren seguimiento del cuidado sin ser el cuidador principal.
    </td>
    <td valign="top">
      <b>4. User Benefits</b><br><br>
      Gestión centralizada de tratamientos y rutinas. Historial completo siempre disponible. Alertas oportunas y coordinación real con otros cuidadores.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>6. Hypotheses</b><br><br>
      Los cuidadores adoptarán la app si la configuración inicial no les toma más de 10 minutos. Las familias valorarán ver el estado del paciente en tiempo real. Compartir perfiles mejorará la coordinación entre turnos.
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

### Segmento Objetivo 1: Cuidadores de personas con discapacidad

**Descripción:**
Este segmento incluye tanto a cuidadores formales —enfermeros, terapeutas, técnicos de salud en atención domiciliaria o en pequeños centros de cuidado— como a informales: familiares o voluntarios que asumen el rol de cuidador principal en casa, muchas veces sin formación específica para ello.

**Características demográficas:**

- **Edad:** 25 a 60 años.
- **Género:** Mayoritariamente femenino —según el INEI (2017), las mujeres representan el 76% de los cuidadores principales en el Perú—, aunque el segmento no excluye a ningún género.
- **Ubicación:** Principalmente zonas urbanas y periurbanas del Perú (Lima Metropolitana, Arequipa, Trujillo, Cusco). En el contexto latinoamericano, el segmento se extiende a países como Colombia, México y Chile.
- **Nivel educativo:** Variable: desde secundaria completa hasta educación superior técnica o universitaria en el caso de cuidadores formales.
- **Ocupación:** Cuidador/a formal (con formación en salud) o cuidador/a informal (familiar sin remuneración o con remuneración parcial).
- **Nivel socioeconómico:** Sectores B, C y D.

**Características conductuales y psicográficas:**

Usan el celular con frecuencia para organizar su vida diaria y muestran disposición a incorporar apps que realmente les faciliten el trabajo. Sin embargo, cargan con una sensación constante de sobrecarga: tienen mucho que coordinar, poco tiempo y, generalmente, ninguna herramienta pensada para ellos. Valoran la simplicidad por encima de todo —si algo les toma demasiado tiempo en aprender, simplemente no lo usan. La mayoría accede desde dispositivos Android de gama media.

**Datos estadísticos de sustento:**

Según el INEI (2017), en el Perú hay aproximadamente 1.57 millones de personas que cumplen el rol de cuidador principal no remunerado. A nivel global, la OMS (2021) estima que más de 53 millones de personas son cuidadores informales, siendo uno de los grupos con mayor prevalencia de burnout y problemas de salud mental.

---

### Segmento Objetivo 2: Familiares de personas con discapacidad

**Descripción:**
Son los familiares directos —padres, madres, hermanos, cónyuge, hijos adultos— que no ejercen el rol de cuidador principal pero quieren saber cómo está su familiar. También incluye a familias que contratan un cuidador externo y necesitan tener algún nivel de supervisión remota sobre la calidad del cuidado que se está brindando.

**Características demográficas:**

- **Edad:** 30 a 65 años.
- **Género:** Sin predominancia marcada; tanto hombres como mujeres buscan información sobre el bienestar de su familiar.
- **Ubicación:** Perú y Latinoamérica, con énfasis en zonas urbanas. En algunos casos, se trata de familiares que viven en el extranjero y necesitan monitorear remotamente el cuidado de alguien en Perú.
- **Nivel educativo:** Secundaria completa a superior universitaria.
- **Ocupación:** Trabajadores dependientes o independientes con jornadas que no les permiten estar presentes junto a su familiar durante el día.
- **Nivel socioeconómico:** Sectores A, B y C.

**Características conductuales y psicográficas:**

La preocupación por el bienestar de su familiar es constante, y eso genera una necesidad genuina de transparencia. Quieren saber qué pasó durante el día sin tener que llamar a cada rato. Están familiarizados con el uso de smartphones y apps de comunicación como WhatsApp o Gmail, y están dispuestos a adoptar nuevas herramientas si les dan esa tranquilidad. Cualquier error o descuido en el cuidado los afecta profundamente.

**Datos estadísticos de sustento:**

El Ministerio de la Mujer y Poblaciones Vulnerables del Perú (MIMP, 2022) señala que el 68% de las familias de personas con discapacidad severa reporta dificultades para conciliar sus responsabilidades laborales con el seguimiento del cuidado. La Encuesta Nacional Especializada sobre Discapacidad (ENEDIS, 2012) estimó que el 87.2% de las personas con discapacidad en el Perú vive en hogares con al menos un familiar directo que asume responsabilidades de soporte y supervisión.

---

*Referencias*

- Instituto Nacional de Estadística e Informática [INEI]. (2017). *Primera Encuesta Nacional Especializada sobre Discapacidad 2012: Resultados definitivos.* Lima: INEI.
- Organización Mundial de la Salud [OMS]. (2021). *World report on disability.* Ginebra: OMS.
- Ministerio de la Mujer y Poblaciones Vulnerables [MIMP]. (2022). *Informe sobre la situación de las personas con discapacidad en el Perú.* Lima: MIMP.
