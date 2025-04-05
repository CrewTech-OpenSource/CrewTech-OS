<div align="center">
  <h1>UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</h1>
</div>

<div align="center">
  <img width = "15%" src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png">
</div>

<div align="center">
  <h2>Ingienería de Software - 2025 - 1</h2>
</div>

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

<div align="center">
    <h1>Abril, 2025</h1>
</div>

## Contenido
### [1.1. Startup Profile](#11-startup-profile)
  #### [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  #### [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
### [1.2. Solution Profile](#12-solution-profile)
  #### [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
  #### [1.2.2. Lean UX Process.](#122-lean-ux-process)
  ##### [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
  ##### [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
  ##### [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
  ##### [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
### [1.3. Segmentos objetivo.](#13-segmentos-objetivo)


## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

DriveCare es una aplicación innovadora diseñada para supervisar constantemente el estado de un vehículo, ayudando así a preservar y prolongar su vida útil. Muchas personas que utilizan su auto tanto de forma personal como profesional enfrentan un problema frecuente: desconocen las condiciones reales de su vehículo. Esto suele llevar a descuidos en el mantenimiento y, eventualmente, a reparaciones costosas cuando los problemas ya se han agravado. 
Por ello, nuestro servicio ofrece la instalación de un sensor en el vehículo, el cual el cliente deberá pagar su uso de manera mensual, que estudia las estadísticas, tendencias y todo tipo de datos. A partir de lo mencionado, nuestra aplicación mostrará, por medio de la app, todo tipo de mala praxis por parte del conductor, correciones, entre otros. Asimismo, recién instalada la aplicación, la aplicación hara una serie de preguntas, para poder leer los datos y tener una mejora en sus predicciones o resultados.
En resumen, a través del sensor, instalado en el carro, se leen los datos, que viajan hacia la aplicación, que se obtiene pagando una suscripción, la cual deja de funcionar en caso el cliente deja de pagar la suscripción.

### 1.1.2. Perfiles de integrantes del equipo

|  |   Descripción   |
|------------|------------|
|<img src="https://github.com/user-attachments/assets/1fd3f295-3f6b-4755-9b15-d71a228ac64e" alt="Dayro imagen" style="width: 300px; margin-right: 20px;"/>|Mi nombre es Dayro Ríos, tengo 18 años, estoy cursando el tercer ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Tengo conocimientos en los lenguajes de programación c++, python, html y css, además gestores de base de datos como mssql. Cuando trabajo en equipo soy comunicativo, responsable y trato de realizar el trabajo lo mejor posible|
|<img src="https://github.com/user-attachments/assets/87875609-8329-4cc2-b8b1-bfc4e400763e" alt="Antonio imagen" style="width: 300px; margin-right: 20px;"/>| Mi nombre es Antonio Jhair Navarro Chinga tengo 19 años y soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Soy colaborativo, responsable y tengo conocimientos en programación estructurada, programación orientada a objetos y algoritmos. |
|<img src="https://github.com/user-attachments/assets/ab04f900-0560-4f57-8aae-1390178ce9ff" alt="Vitaly imagen" style="width: 250px; margin-right: 20px;"/> | Mi nombre es Vitaly Baca Camargo, Tengo 19 años y actualmente estudio la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Tengo conocimiento en SQL y C ++, programación orientada objetos y estructura de datos. Además de HTML y CSS. Me considero una persona responsable y comprometida en mis trabajos, por lo que siempre intento ayudar a mi grupo con cualquier duda.|
| <img src="https://github.com/user-attachments/assets/97bad99c-cdc5-4efc-bbd7-6875d42cbf56" alt="Moises imagen" style="width: 250px; margin-right: 20px;"/> | Mi nombre es Moisés Espinoza Chávez, estoy estudiando la carrera de Ingeniería de Software y actualmente me encuentro cursando el quinto ciclo. Me gusta el deporte y mantenerme en constante aprendizaje, a menudo disfruto pasar tiempo con amigos, escuchar música o leer algo, considero que tengo habilidades para la adaptabilidad, así como la responsabilidad. |
|<img src="https://github.com/user-attachments/assets/135bcaa9-9c65-4918-ac1f-1e78052c668b" alt="Sergio imagen" style="width: 250px; margin-right: 20px;"/> | Mi nombre es Sergio Gino Julca Minaya, con código u202318274. Actualmente soy estudiante del 5to ciclo de la carrera de Ingienería de Software, con conocimiento de html, css, desarrollo agile, método scrum, entre otros. Asimismo, me considero una persona constante, autodidacta, responsable y me gusta trabajar en equipo, de esta manera apoyaré a mi grupo en todo momento. |


## 1.2 Solution Profile
Nuestro producto se centra en realizar una aplicación diseñada para poder conectar a las personas interesadas que buscan prevenir el deterioro de sus vehículos y optimizar su mantenimiento mediante un sistema de monitoreo avanzado.
El desafío surge ya que muchos propietarios de vehículos enfrentan fallas mecánicas imprevistas, mantenimientos costosos y pérdida de rendimiento debido a la falta de información en tiempo real sobre el estado del automóvil y los hábitos de conducción. Esta problemática, común en usuarios con rutinas exigentes o poco conocimiento técnico, conlleva riesgos innecesarios, altos gastos y una reducción significativa en la durabilidad del vehículo. 
Con el objetivo de brindar una solución efectiva, surge DriveCare, una innovadora aplicación que, en conjunto con un sensor instalado en el vehículo, analiza constantemente datos como el comportamiento del conductor, el estado técnico del auto y las tendencias de uso. Mediante inteligencia artificial, la plataforma identifica malas prácticas, recomienda acciones correctivas y anticipa posibles fallos, permitiendo una intervención temprana antes de que surjan problemas mayores.
Este servicio opera bajo un modelo de suscripción mensual. Al estar activo, el usuario tiene acceso completo a todas las funcionalidades de la app. En caso de cancelación o falta de pago, el acceso queda suspendido, garantizando así la continuidad del servicio solo para clientes activos.
Nuestra misión es transformar la manera en que los conductores cuidan sus vehículos, ofreciendo una herramienta tecnológica que promueve una conducción responsable, reduce costos por reparaciones y maximiza el tiempo de vida del automóvil. Con DriveCare, conducir no solo será más seguro, sino también más inteligente.

