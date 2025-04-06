<div align="center"><h1>UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</h1></div>
<div align="center"><img width = "15%" src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></div>
<div align="center"> <h2>INGIENERÍA DE SOFTWARE - 2025 - 10</h2> </div>

### Desarrollo de Aplicaciones Open Source - 1ASI0729
### Sección: 4294
### Profesor: Angel Augusto Velasquez Nuñez
### "Informe de Trabajo Final"
### Startup: CrewTech
### Nombre del producto: DriveCare
| Estudiante |   Código   |
|------------|------------|
| Baca Camargo, Vitaly Arturo    |   u20231c426    |
| Moises      |  Cell 5    |
| Julca Minaya, Sergio Gino      |   u202318274    |
| Navarro Chinga, Antonio Jhair  |   u202314101    |
| Rios Piñan, Dayro Richard      |   u202315283    |

<div align="center"> <h1>Abril, 2025</h1> </div>

# REGISTRO DE VERSIONES DEL INFOERME

# PROJECT REPORT COLLABORATION INSIGHTS

# CONTENIDO 
## [Capítulo I: Introducción](#capitulo-1)
### [1.1. Startup Profile](#startup-profile)
  #### [1.1.1. Descripción de la Startup](#descripción-de-la-startup)
  #### [1.1.2. Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)
### [1.2. Solution Profile](#solution-profile)
  #### [1.2.1. Antecedentes y problemática](#antecedentes-y-problematica)
  #### [1.2.2. Lean UX Process](#lean-ux-process)
  ##### [1.2.2.1. Lean UX Problem Statements](#lean-ux-problem-statements)
  ##### [1.2.2.2. Lean UX Assumptions](#lean-ux-assumptions)
  ##### [1.2.2.3. Lean UX Hypothesis Statements](#lean-ux-hypothesis-statements)
  ##### [1.2.2.4. Lean UX Canvas](#lean-ux-canvas)
### [1.3. Segmentos objetivos](#segmentos-objetivos)

## [Capítulo II: Requirements Elicitation & Analysis](#capitulo-2)
### [2.1. Competidores](#competidores)
  #### [2.1.1. Análisis competitivo](#análisis-competitivo)
  #### [2.1.2. Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)
### [2.2. Entrevistas](#entrevistas)
  #### [2.2.1. Diseño de entrevistas](#diseño-de-entrevistas)
  #### [2.2.2. Registro de entrevistas](#registro-de-entrevistas)
  #### [2.2.3. Análisis de entrevistas](#análisis-de-entrevistas)
### [2.3. Solution Profile](#solution-profile)
  #### [2.3.1. User Personas](#user-personas)
  #### [2.3.2. User Task Matrix](#user-task-matrix)
  #### [2.3.3. User Journey Mapping](#user-journey-mapping)
  #### [2.3.4. Empathy Mapping](#empathy-mapping)
  #### [2.3.5. As-is Scenario Mapping](#as-is-scenario-mapping)
### [2.4. Ubiquitous Language](#ubiquitous-language)

## [Capítulo III: Requirements Specification](#capitulo-3)
### [3.1. To-Be Scenario Mapping](#to-be-scenario-mapping)
### [3.2. User Stories](#user-stories)
### [3.3. Impact Mapping](#impact-mapping)
### [3.4. Product Backlog](#product-backlog)
  
## [Capítulo IV: Product Design](#capitulo-4)
### [4.1. Style Guidelines](#style-guidelines)
  #### [4.1.1. General Style Guidelines](#general-style-guidelines)
  #### [4.1.2. Web Style Guidelines](#web-style-guidelines)
### [4.2. Information Architecture](#information-architecture)
  #### [4.2.1. Organization Systems](#organization-systems)
  #### [4.2.2. Labeling Systems](#labeling-systems)
  #### [4.2.3. SEO Tags and Meta Tags](#seo-tags-and-meta-tags)
  #### [4.2.4. Searching Systems](#searching-systems)
  #### [4.2.5. Navigation Systems](#navigation-systems)
### [4.3. Landing Page UI Design](#landing-page-ui-design)
  #### [4.3.1. Landing Page Wireframe](#landing-page-wireframe)
  #### [4.3.2. Landing Page Mock-up](#landing-page-mock-up)
### [4.4. Web Applications UX/UI Design](#web-applications-uxui-design)
  #### [4.4.1. Web Applications Wireframes](#web-applications-wireframes)
  #### [4.4.2. Web Applications Wireflow Diagrams](#web-applications-wireflow-diagrams)
  #### [4.4.3. Web Applications Mock-ups](#web-applications-mock-ups)
  #### [4.4.4. Web Applications User Flow Diagrams](#web-applications-user-flow-diagrams)
### [4.5. Web Applications Prototyping](#web-applications-prototyping)
### [4.6. Domain-Driven Software Architecture](#domain-driven-software-architecture)
  #### [4.6.1. Software Architecture Context Diagram](#software-architecture-context-diagram)
  #### [4.6.2. Software Architecture Container Diagrams](#software-architecture-container-diagrams)
  #### [4.6.3. Software Architecture Components Diagrams](#software-architecture-components-diagrams)
### [4.7. Software Object-Oriented Design](#software-object-oriented-design)
  #### [4.7.1. Class Diagrams](#class-diagrams)
  #### [4.7.2. Class Dictionary](#class-dictionary)
### [4.8. Database Design](#database-design)
  #### [4.8.1. Database Diagram](#database-diagram)
  
## [Capítulo V: Product Implementation, Validation & Deployment](#capitulo-5)

## Conclusiones

## Bibliografía

## Anexos

# STUDENT OUTCOME

# CAPITULO 1
## Startup Profile

### Descripción de la Startup
DriveCare es una aplicación innovadora diseñada para supervisar constantemente el estado de un vehículo, ayudando así a preservar y prolongar su vida útil. Muchas personas que utilizan su auto tanto de forma personal como profesional enfrentan un problema frecuente: desconocen las condiciones reales de su vehículo. Esto suele llevar a descuidos en el mantenimiento y, eventualmente, a reparaciones costosas cuando los problemas ya se han agravado. 
Por ello, nuestro servicio ofrece la instalación de un sensor en el vehículo, el cual el cliente deberá pagar su uso de manera mensual, que estudia las estadísticas, tendencias y todo tipo de datos. A partir de lo mencionado, nuestra aplicación mostrará, por medio de la app, todo tipo de mala praxis por parte del conductor, correciones, entre otros. Asimismo, recién instalada la aplicación, la aplicación hara una serie de preguntas, para poder leer los datos y tener una mejora en sus predicciones o resultados.
En resumen, a través del sensor, instalado en el carro, se leen los datos, que viajan hacia la aplicación, que se obtiene pagando una suscripción, la cual deja de funcionar en caso el cliente deja de pagar la suscripción.

### Perfiles de integrantes del equipo
|  |   Descripción   |
|------------|------------|
|<img src="https://github.com/user-attachments/assets/1fd3f295-3f6b-4755-9b15-d71a228ac64e" alt="Dayro imagen" style="width: 300px; margin-right: 20px;"/>|Mi nombre es Dayro Ríos, tengo 18 años, estoy cursando el tercer ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Tengo conocimientos en los lenguajes de programación c++, python, html y css, además gestores de base de datos como mssql. Cuando trabajo en equipo soy comunicativo, responsable y trato de realizar el trabajo lo mejor posible|
|<img src="https://github.com/user-attachments/assets/87875609-8329-4cc2-b8b1-bfc4e400763e" alt="Antonio imagen" style="width: 300px; margin-right: 20px;"/>| Mi nombre es Antonio Jhair Navarro Chinga tengo 19 años y soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Soy colaborativo, responsable y tengo conocimientos en programación estructurada, programación orientada a objetos y algoritmos. |
|<img src="https://github.com/user-attachments/assets/ab04f900-0560-4f57-8aae-1390178ce9ff" alt="Vitaly imagen" style="width: 250px; margin-right: 20px;"/> | Mi nombre es Vitaly Baca Camargo, Tengo 19 años y actualmente estudio la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Tengo conocimiento en SQL y C ++, programación orientada objetos y estructura de datos. Además de HTML y CSS. Me considero una persona responsable y comprometida en mis trabajos, por lo que siempre intento ayudar a mi grupo con cualquier duda.|
| <img src="https://github.com/user-attachments/assets/97bad99c-cdc5-4efc-bbd7-6875d42cbf56" alt="Moises imagen" style="width: 250px; margin-right: 20px;"/> | Mi nombre es Moisés Espinoza Chávez, estoy estudiando la carrera de Ingeniería de Software y actualmente me encuentro cursando el quinto ciclo. Me gusta el deporte y mantenerme en constante aprendizaje, a menudo disfruto pasar tiempo con amigos, escuchar música o leer algo, considero que tengo habilidades para la adaptabilidad, así como la responsabilidad. |
|<img src="https://github.com/user-attachments/assets/135bcaa9-9c65-4918-ac1f-1e78052c668b" alt="Sergio imagen" style="width: 250px; margin-right: 20px;"/> | Mi nombre es Sergio Gino Julca Minaya, con código u202318274. Actualmente soy estudiante del 5to ciclo de la carrera de Ingienería de Software, con conocimiento de html, css, desarrollo agile, método scrum, entre otros. Asimismo, me considero una persona constante, autodidacta, responsable y me gusta trabajar en equipo, de esta manera apoyaré a mi grupo en todo momento. |

## Solution Profile
Nuestro producto se centra en realizar una aplicación diseñada para poder conectar a las personas interesadas que buscan prevenir el deterioro de sus vehículos y optimizar su mantenimiento mediante un sistema de monitoreo avanzado.
El desafío surge ya que muchos propietarios de vehículos enfrentan fallas mecánicas imprevistas, mantenimientos costosos y pérdida de rendimiento debido a la falta de información en tiempo real sobre el estado del automóvil y los hábitos de conducción. Esta problemática, común en usuarios con rutinas exigentes o poco conocimiento técnico, conlleva riesgos innecesarios, altos gastos y una reducción significativa en la durabilidad del vehículo. 
Con el objetivo de brindar una solución efectiva, surge DriveCare, una innovadora aplicación que, en conjunto con un sensor instalado en el vehículo, analiza constantemente datos como el comportamiento del conductor, el estado técnico del auto y las tendencias de uso. Mediante inteligencia artificial, la plataforma identifica malas prácticas, recomienda acciones correctivas y anticipa posibles fallos, permitiendo una intervención temprana antes de que surjan problemas mayores.
Este servicio opera bajo un modelo de suscripción mensual. Al estar activo, el usuario tiene acceso completo a todas las funcionalidades de la app. En caso de cancelación o falta de pago, el acceso queda suspendido, garantizando así la continuidad del servicio solo para clientes activos.
Nuestra misión es transformar la manera en que los conductores cuidan sus vehículos, ofreciendo una herramienta tecnológica que promueve una conducción responsable, reduce costos por reparaciones y maximiza el tiempo de vida del automóvil. Con DriveCare, conducir no solo será más seguro, sino también más inteligente.

### Antecedentes y problematica

### Lean UX Process
lorem

#### Lean UX Problem Statements
- A pesar de que los propietarios de vehículos son conscientes de la importancia del mantenimiento preventivo, muchos de ellos olvidan o descuidan realizar las acciones necesarias para evitar fallas en sus vehículos. Esto provoca un aumento en las reparaciones inesperadas y en los costos asociados, además de generar inconvenientes y preocupaciones para los propietarios de los vehículos.
   - ***¿Cómo podemos ayudar a los propietarios de vehículos a llevar un control más eficiente del mantenimiento preventivo para evitar fallas inesperadas y reducir los costos de reparación?***
  
- Los vehículos modernos están equipados con tecnologías avanzadas, pero los propietarios a menudo carecen de una forma sencilla y accesible de monitorear el estado de su vehículo en tiempo real. Esto crea incertidumbre sobre el funcionamiento del vehículo y aumenta el riesgo de que se pasen por alto posibles fallas que podrían haberse pre*venido.
    - ***¿Cómo podemos brindar a los propietarios de vehículos información en tiempo real sobre el estado de su vehículo, permitiéndoles tomar decisiones informadas y oportunas sobre su mantenimiento?***

#### Lean UX Assumptions

#### Lean UX Hypothesis Statements

#### Lean UX Canvas

## Segmentos objetivos

## Competidores
### Análisis competitivo
lorem

### Estrategias y tácticas frente a competidores
lorem

## Entrevistas
### Diseño de entrevistas
lorem

### Registro de entrevistas
lorem

### Análisis de entrevistas
lorem

## Solution Profile
### User Personas
lorem

### User Task Matrix
lorem

### User Journey Mapping
lorem

### Empathy Mapping
lorem

### As-is Scenario Mapping
lorem

## Ubiquitous Language
lorem


## To-Be Scenario Mapping
Contenido aquí...

## User Stories
Contenido aquí...

## Impact Mapping
Contenido aquí...

## Product Backlog
Contenido aquí...

## Style Guidelines
Contenido aquí...

### General Style Guidelines
Contenido aquí...

### Web Style Guidelines
Contenido aquí...

## Information Architecture
Contenido aquí...

### Organization Systems
Contenido aquí...

### Labeling Systems
Contenido aquí...

### SEO Tags and Meta Tags
Contenido aquí...

### Searching Systems
Contenido aquí...

### Navigation Systems
Contenido aquí...

## Landing Page UI Design
Contenido aquí...

### Landing Page Wireframe
Contenido aquí...

### Landing Page Mock-up
Contenido aquí...

## Web Applications UX/UI Design
Contenido aquí...

### Web Applications Wireframes
Contenido aquí...

### Web Applications Wireflow Diagrams
Contenido aquí...

### Web Applications Mock-ups
Contenido aquí...

### Web Applications User Flow Diagrams
Contenido aquí...

## Web Applications Prototyping
Contenido aquí...

## Domain-Driven Software Architecture
Contenido aquí...

### Software Architecture Context Diagram
Contenido aquí...

### Software Architecture Container Diagrams
Contenido aquí...

### Software Architecture Components Diagrams
Contenido aquí...

## Software Object-Oriented Design
Contenido aquí...

### Class Diagrams
Contenido aquí...

### Class Dictionary
Contenido aquí...

## Database Design
Contenido aquí...

### Database Diagram
Contenido aquí...
