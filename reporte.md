# Student Outcome

El curso de Aplicaciones para Dispositivos Móviles contribuye al cumplimiento del
Student Outcome ABET:

**ABET - EAC - Student Outcome 7**

**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea
necesario, utilizando estrategias de aprendizaje apropiadas.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones
por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET –
EAC - Student Outcome 7.

| Criterio específico | Acciones realizadas | Conclusiones |
|---|---|---|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | Durante el desarrollo del proyecto CareConnect, el equipo investigó y aplicó tecnologías de desarrollo móvil multiplataforma (Flutter), integración con servicios RESTful propios y de terceros, y principios de Domain-Driven Design, los cuales no habían sido abordados en profundidad con anterioridad. Cada integrante realizó investigación autónoma y colaborativa sobre las herramientas y frameworks requeridos para la construcción de la solución. | El estudio continuo de nuevas tecnologías resultó fundamental para dar respuesta a los requerimientos técnicos del proyecto. Los integrantes demostraron capacidad de aprender de forma autónoma y aplicar dichos conocimientos en el desarrollo de software de calidad. |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software. | El equipo identificó brechas de conocimiento en áreas como arquitectura de software orientada a dominios (DDD), diseño UX/UI para aplicaciones de salud, y normativa relacionada a la privacidad de datos de pacientes. Se tomaron acciones para cerrar dichas brechas mediante investigación bibliográfica, revisión de documentación oficial y consulta de recursos especializados. | El proyecto evidenció que el campo del desarrollo de software evoluciona constantemente y que la capacidad de adaptación y aprendizaje continuo es una competencia indispensable para el desempeño profesional de cualquier ingeniero de software. |

---

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**CareLink** es una startup de tecnología enfocada en el sector salud y bienestar social,
fundada por un equipo de estudiantes de Ingeniería de Software de la Universidad
Peruana de Ciencias Aplicadas (UPC). Nació a partir de la necesidad identificada de
brindar herramientas digitales que faciliten el trabajo de cuidadores formales e
informales de personas con discapacidades mentales y/o físicas, así como apoyar a
las propias personas bajo cuidado y a sus familias.

**Misión:** Empoderar a cuidadores y familias de personas con discapacidades mediante
tecnología móvil accesible e intuitiva, que permita un seguimiento integral del bienestar
del paciente y una coordinación eficiente entre todos los involucrados en su cuidado.

**Visión:** Ser la plataforma de referencia en Latinoamérica para la gestión del cuidado
de personas con discapacidad, contribuyendo a mejorar su calidad de vida y la de sus
cuidadores a través de soluciones tecnológicas innovadoras y centradas en el ser humano.

**Producto:** **CareConnect** es una aplicación móvil nativa y multiplataforma diseñada
para el monitoreo de rutinas, gestión de tratamientos y comunicación entre cuidadores
de personas con discapacidades mentales y/o físicas. Entre sus funcionalidades
principales se encuentran:

1. Calendario de toma de pastillas y terapias programadas.
2. Sistema de alertas y recordatorios en tiempo real.
3. Carpeta digital con documentos y tratamientos de los pacientes.
4. Historial y registro de notas con las mejoras del paciente.
5. Compartición de perfiles de pacientes entre cuidadores para garantizar continuidad en el cuidado.

### 1.1.2. Perfiles de integrantes del equipo

> *Nota: Los perfiles de cada integrante del equipo serán completados por el responsable de cada sección correspondiente, incluyendo foto, nombres y apellidos, código de estudiante, carrera y párrafo de resumen de conocimientos técnicos y habilidades.*

| Integrante | Código | Carrera | Resumen |
|---|---|---|---|
| *(Apellido, Nombre)* | *(Código)* | Ingeniería de Software | *(Descripción de conocimientos técnicos y habilidades)* |
| *(Apellido, Nombre)* | *(Código)* | Ingeniería de Software | *(Descripción de conocimientos técnicos y habilidades)* |
| *(Apellido, Nombre)* | *(Código)* | Ingeniería de Software | *(Descripción de conocimientos técnicos y habilidades)* |
| *(Apellido, Nombre)* | *(Código)* | Ingeniería de Software | *(Descripción de conocimientos técnicos y habilidades)* |
| *(Apellido, Nombre)* | *(Código)* | Ingeniería de Software | *(Descripción de conocimientos técnicos y habilidades)* |

---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y Problemática

#### Antecedentes

En el Perú, según el Instituto Nacional de Estadística e Informática (INEI), más de
3 millones de personas presentan algún tipo de discapacidad, representando
aproximadamente el 10.4% de la población total (INEI, 2017). De este grupo, una
proporción significativa requiere cuidado permanente por parte de familiares o
profesionales de la salud. Sin embargo, la coordinación entre múltiples cuidadores
suele ser manual, fragmentada y propensa a errores, lo que puede comprometer la
salud y seguridad del paciente.

A nivel global, la Organización Mundial de la Salud (OMS, 2021) señala que la
carga que recae sobre los cuidadores informales —generalmente familiares— es uno
de los principales factores de agotamiento y deterioro de la salud mental en adultos.
La falta de herramientas digitales específicas para este contexto agrava la situación,
ya que las soluciones existentes en el mercado están orientadas principalmente a
entornos clínicos institucionales, dejando de lado el cuidado domiciliario y
comunitario.

#### Problemática — Técnica The 5W's y 2H's

**Who (¿Quiénes?):**
Los principales afectados son los cuidadores —tanto formales (enfermeros, terapeutas)
como informales (familiares, voluntarios)— de personas con discapacidades mentales
y/o físicas. Asimismo, las propias personas con discapacidad y sus familias se ven
impactadas por la falta de coordinación y seguimiento estructurado en sus rutinas de
cuidado.

**What (¿Qué?):**
El problema central es la ausencia de una plataforma digital centralizada que permita
gestionar de forma integrada los tratamientos, rutinas, documentos clínicos y el
historial de progreso de personas con discapacidad, dificultando la coordinación entre
múltiples cuidadores y la toma de decisiones informadas.

**Where (¿Dónde?):**
Este problema se presenta principalmente en entornos de cuidado domiciliario y
comunitario en Perú, aunque también es extensible a toda Latinoamérica, donde la
infraestructura de salud pública no cubre la totalidad de las necesidades de atención
de personas con discapacidad.

**When (¿Cuándo?):**
La problemática se manifiesta de manera constante en la vida diaria de los cuidadores
y pacientes: al coordinar horarios de medicación, al transferir responsabilidades entre
turnos de cuidado, al consultar historiales clínicos y al reportar avances o retrocesos
en la condición del paciente.

**Why (¿Por qué?):**
La causa raíz del problema radica en que el cuidado de personas con discapacidad
es multidimensional y requiere la participación de múltiples actores (médicos,
terapeutas, familiares, cuidadores), pero no existen herramientas accesibles y móviles
que centralicen y sincronicen toda esta información. La consecuencia es que los
cuidadores toman decisiones con información incompleta o desactualizada, poniendo
en riesgo el bienestar del paciente.

**How (¿Cómo?):**
La problemática se materializa en situaciones como: medicación administrada
incorrectamente por falta de comunicación entre cuidadores, pérdida de documentos
clínicos importantes, terapias omitidas o duplicadas, y dificultad para identificar
patrones de mejora o deterioro en el paciente a lo largo del tiempo.

**How Much (¿Cuánto?):**
Según la OMS (2021), alrededor del 15% de la población mundial vive con algún tipo
de discapacidad. En el Perú, el INEI estima que existen más de 1.5 millones de
personas que actúan como cuidadores principales, muchos de los cuales dedican
entre 8 y 12 horas diarias al cuidado de un familiar. El impacto económico de la falta
de herramientas eficientes de coordinación incluye costos asociados a errores en la
medicación, hospitalizaciones evitables y pérdida de productividad laboral de los
cuidadores.

---

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1 — Cuidadores de personas con discapacidad:**

Nuestro contexto revela que los cuidadores de personas con discapacidades mentales
y/o físicas —tanto formales como informales— gestionan rutinas complejas de
medicación, terapias y seguimiento médico de forma manual o con herramientas
genéricas (libretas, WhatsApp, hojas de cálculo) que no están diseñadas para este
propósito.

Hemos observado que el factor crítico que afecta negativamente a los cuidadores es
la falta de una plataforma centralizada que les permita sincronizar información con
otros cuidadores, acceder rápidamente al historial del paciente y recibir alertas
oportunas.

¿Cómo podríamos diseñar una solución móvil que centralice la gestión del cuidado,
facilite la comunicación entre cuidadores y reduzca los riesgos derivados de la
descoordinación?

**Problem Statement 2 — Familiares de personas con discapacidad:**

Nuestro contexto revela que los familiares de personas con discapacidad tienen
dificultades para mantenerse informados sobre el estado y progreso de su familiar
cuando este se encuentra bajo el cuidado de un tercero (cuidador profesional, centro
de atención).

Hemos observado que el factor crítico es la ausencia de un canal de comunicación
estructurado que les permita ver el registro de actividades, tratamientos y evolución
del paciente en tiempo real.

¿Cómo podríamos brindar a las familias visibilidad y tranquilidad sobre el cuidado
de su familiar mediante una herramienta digital accesible y fácil de usar?

---

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. Creemos que existe una demanda significativa de aplicaciones móviles especializadas
   en la gestión del cuidado de personas con discapacidad en Perú y Latinoamérica.
2. Creemos que los cuidadores están dispuestos a adoptar herramientas digitales si
   estas son intuitivas, rápidas de configurar y no requieren formación técnica especializada.
3. Creemos que un modelo freemium (funcionalidades básicas gratuitas y avanzadas de pago)
   permitirá capturar tanto a usuarios individuales como a instituciones de salud.
4. Creemos que la coordinación deficiente entre cuidadores genera costos evitables
   que justifican la adopción de nuestra solución.

**User Assumptions:**

1. **¿Quién es el usuario?** Cuidadores formales e informales de personas con
   discapacidades mentales y/o físicas, y familiares de las personas bajo cuidado.
2. **¿Dónde encaja nuestro producto en su vida?** En su rutina diaria de cuidado:
   al administrar medicamentos, registrar terapias, documentar el progreso del paciente
   y coordinar con otros cuidadores.
3. **¿Qué problema resuelve?** La descoordinación, la pérdida de información y la
   falta de visibilidad sobre el estado del paciente entre múltiples cuidadores.
4. **¿Cuándo y cómo se usa?** Principalmente desde un smartphone, varias veces al
   día: al inicio y fin de cada turno de cuidado, al administrar medicamentos y al
   registrar observaciones del paciente.
5. **¿Qué características son importantes?** Alertas de medicación, calendario de
   terapias, notas de evolución, compartición de perfiles de pacientes y almacenamiento
   de documentos clínicos.
6. **¿Cómo debe verse y comportarse el producto?** Limpio, accesible y confiable.
   Diseñado para ser utilizado bajo condiciones de estrés, con flujos simples y mínima
   fricción para el registro de información.

---

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis 1:**

Creemos que lograremos que los cuidadores administren de forma más segura y
coordinada los tratamientos de sus pacientes **si** ofrecemos un calendario
integrado de medicación y terapias con alertas en tiempo real **para** cuidadores
formales e informales de personas con discapacidad.

**Sabremos que tenemos éxito cuando** el 70% de los usuarios activos use la
función de alertas de medicación al menos una vez al día durante las primeras
4 semanas de uso.

---

**Hypothesis 2:**

Creemos que lograremos que las familias se sientan más tranquilas respecto al
cuidado de su familiar **si** les proporcionamos acceso en tiempo real al historial
de actividades; notas de evolución y estado del paciente **para** los familiares
de personas bajo cuidado de terceros.

**Sabremos que tenemos éxito cuando** el 60% de los perfiles de pacientes tenga
al menos un familiar vinculado y activo en la plataforma al finalizar el primer mes.

---

**Hypothesis 3:**

Creemos que lograremos una transición fluida del cuidado entre turnos **si**
implementamos una función de compartición de perfiles de pacientes con historial
completo **para** cuidadores que se alternan en el cuidado de una misma persona.

**Sabremos que tenemos éxito cuando** el tiempo promedio de transferencia de
información entre cuidadores al cambio de turno se reduzca en un 50%
respecto al proceso manual, según los registros de actividad de la app.

---

#### 1.2.2.4. Lean UX Canvas

| | |
|---|---|
| **Business Problem** | Los cuidadores de personas con discapacidad gestionan información crítica de salud de forma desorganizada y sin herramientas especializadas, generando riesgos para el paciente y agotamiento en el cuidador. |
| **Business Outcomes** | Reducción de errores de medicación. Mejora en la coordinación entre cuidadores. Adopción sostenida de la plataforma con tasas de retención superiores al 60% al mes 3. |
| **Users & Customers** | Segmento 1: Cuidadores formales e informales de personas con discapacidad. Segmento 2: Familiares de personas con discapacidad que requieren seguimiento del cuidado. |
| **User Benefits** | Gestión centralizada de tratamientos y rutinas. Visibilidad total del historial del paciente. Alertas oportunas y coordinación fluida con otros cuidadores. |
| **Solution Ideas** | App móvil multiplataforma con: calendario de medicación y terapias, sistema de alertas, carpeta de documentos, historial de evolución y compartición de perfiles de pacientes. |
| **Hypotheses** | Los cuidadores adoptarán la app si la configuración inicial toma menos de 10 minutos. Las familias valorarán el acceso en tiempo real al estado del paciente. La compartición de perfiles mejorará la coordinación entre turnos. |
| **What's the most important thing we need to learn first?** | ¿Los cuidadores están dispuestos a registrar información durante su rutina de trabajo, o perciben esto como una carga adicional? |
| **What's the least amount of work we need to do to learn the next most important thing?** | Entrevistas con al menos 6 cuidadores (3 formales y 3 informales) para validar los flujos de trabajo actuales y los puntos de mayor fricción en la gestión del cuidado. |

---

## 1.3. Segmentos Objetivo

CareConnect identifica dos segmentos objetivo principales, definidos a partir del
análisis del dominio del problema y de la problemática identificada:

---

### Segmento Objetivo 1: Cuidadores de personas con discapacidad

**Descripción:**
Este segmento comprende tanto a cuidadores formales (enfermeros, terapeutas,
técnicos de salud que trabajan en atención domiciliaria o en pequeños centros de
cuidado) como a cuidadores informales (familiares o voluntarios que asumen el rol
de cuidador principal en el hogar).

**Características demográficas:**

- **Edad:** 25 a 60 años.
- **Género:** Predominantemente femenino (según el INEI, 2017, las mujeres representan
  el 76% de los cuidadores principales en el Perú), aunque el segmento incluye
  cuidadores de cualquier género.
- **Ubicación geográfica:** Principalmente en zonas urbanas y periurbanas del Perú
  (Lima Metropolitana, Arequipa, Trujillo, Cusco). En el contexto latinoamericano,
  el segmento se extiende a países como Colombia, México y Chile.
- **Nivel educativo:** Variable; desde secundaria completa hasta educación superior
  técnica o universitaria en el caso de cuidadores formales.
- **Ocupación:** Cuidador/a formal (con formación técnica o profesional en salud)
  o cuidador/a informal (familiar que asume el rol de forma no remunerada o
  semi-remunerada).
- **Nivel socioeconómico:** Sectores B, C y D.

**Características conductuales y psicográficas:**

- Alta disposición al uso de aplicaciones móviles para organizar su vida cotidiana.
- Sensación frecuente de agotamiento y sobrecarga de responsabilidades.
- Necesidad de comunicación fluida con otros cuidadores involucrados en el cuidado
  del paciente.
- Valoración de la simplicidad y rapidez en el uso de herramientas digitales.
- Acceso predominante a través de dispositivos Android de gama media.

**Datos estadísticos de sustento:**

Según el INEI (2017), en el Perú existen aproximadamente 1.57 millones de personas
que se desempeñan como cuidadores principales no remunerados. De acuerdo con la
OMS (2021), a nivel global más de 53 millones de personas actúan como cuidadores
informales, siendo este uno de los grupos laborales con mayor prevalencia de burnout
y trastornos de salud mental.

---

### Segmento Objetivo 2: Familiares de personas con discapacidad

**Descripción:**
Este segmento comprende a los familiares directos (padre, madre, hermanos, cónyuge,
hijos adultos) de personas con discapacidad que no ejercen el rol de cuidador principal
pero que desean mantenerse informados sobre el estado y progreso de su familiar.
También incluye a familias que contratan un cuidador externo y requieren supervisar
de forma remota la calidad del cuidado brindado.

**Características demográficas:**

- **Edad:** 30 a 65 años.
- **Género:** Sin predominancia marcada de género; tanto hombres como mujeres
  buscan información sobre el bienestar de su familiar.
- **Ubicación geográfica:** Perú y Latinoamérica, con énfasis en zonas urbanas.
  En algunos casos, familiares que residen en el extranjero y requieren monitoreo
  remoto del cuidado de su familiar en Perú.
- **Nivel educativo:** Secundaria completa a superior universitaria.
- **Ocupación:** Trabajadores dependientes o independientes con jornadas laborales
  que no les permiten estar presentes de forma continua junto a su familiar con
  discapacidad.
- **Nivel socioeconómico:** Sectores A, B y C.

**Características conductuales y psicográficas:**

- Alta preocupación por el bienestar y seguridad de su familiar con discapacidad.
- Deseo de transparencia y acceso en tiempo real a la información sobre el cuidado
  del paciente.
- Disposición a adoptar tecnología que les brinde tranquilidad y control sobre la
  situación de su familiar.
- Uso habitual de smartphones y aplicaciones de comunicación (WhatsApp, Gmail,
  redes sociales).
- Sensibilidad ante errores o descuidos en el cuidado de su familiar.

**Datos estadísticos de sustento:**

De acuerdo con el Ministerio de la Mujer y Poblaciones Vulnerables del Perú (MIMP,
2022), el 68% de las familias de personas con discapacidad severa reportan dificultades
para conciliar sus responsabilidades laborales con el seguimiento del cuidado de su
familiar. La Encuesta Nacional Especializada sobre Discapacidad (ENEDIS, 2012)
estimó que el 87.2% de las personas con discapacidad en el Perú vive en hogares
con algún familiar directo que asume responsabilidades de soporte y supervisión de
su cuidado.

---

*Referencias*

- Instituto Nacional de Estadística e Informática [INEI]. (2017). *Primera Encuesta
  Nacional Especializada sobre Discapacidad 2012: Resultados definitivos.* Lima: INEI.
- Organización Mundial de la Salud [OMS]. (2021). *World report on disability.*
  Ginebra: OMS.
- Ministerio de la Mujer y Poblaciones Vulnerables [MIMP]. (2022). *Informe sobre
  la situación de las personas con discapacidad en el Perú.* Lima: MIMP.
