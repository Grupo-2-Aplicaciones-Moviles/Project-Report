# Capítulo 4: Product Implementation & Validation #

## _4.1. Software Configuration Management_ ##

Esta guía define las decisiones y acuerdos fundamentales para el desarrollo, mantenimiento y despliegue de la aplicación **WeRide**, que gestiona el alquiler de vehículos. El objetivo es asegurar la coherencia, eficiencia y calidad a lo largo del ciclo de vida del proyecto.

### 4.1.1. Software Development Environment Configuration ###

En esta sección, se explica los entornos en donde se decidió llevar a cabo el ciclo de vida de desarrollo de los productos de software relacionados al proyecto del curso.

<table border="1">
  <tr>
    <td>Project Management</td>
    <td><h4>Github</h4>Plataforma en línea que permite almacenar código fuente en repositorios. Gracias a la tecnología de control de versiones Git, se puede organizar el código y facilitar el trabajo colaborativo en equipo.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>WhatsApp</h4>Aplicación de mensajería instantánea utilizada para la comunicación del equipo, coordinación de actividades y envío de recordatorios de reuniones.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Trello</h4>Software de administración y gestión de proyectos utilizado para establecer, organizar y asignar las tareas del equipo.</td>
  </tr>

  <tr>
    <td>Requirements Management</td>
    <td><h4>Miro</h4>Plataforma colaborativa en línea utilizada para la gestión de requisitos, organización de ideas y elaboración de diagramas y flujos de trabajo de manera visual.</td>
  </tr>

  <tr>
    <td>Product UX/UI Design</td>
    <td><h4>Figma</h4>Aplicación que permite el diseño de interfaces mediante herramientas colaborativas, facilitando la creación de prototipos interactivos y experiencias de usuario.</td>
  </tr>

  <tr>
    <td>Software Development</td>
    <td><h4>Git</h4>Sistema de control de versiones utilizado para gestionar cambios en el código fuente y facilitar el trabajo colaborativo.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Node.js</h4>Entorno de ejecución de JavaScript del lado del servidor que permite desarrollar aplicaciones web escalables y de alto rendimiento.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>HTML</h4>Lenguaje de marcado utilizado para la estructuración y presentación del contenido en páginas web.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>CSS</h4>Lenguaje utilizado para estilizar y dar formato visual a documentos HTML.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>TypeScript</h4>Lenguaje de programación basado en JavaScript que añade tipado estático y facilita el desarrollo de aplicaciones web escalables.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>VSCode</h4>Editor de código fuente que ofrece múltiples extensiones y herramientas para agilizar el desarrollo de software.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>WebStorm</h4>Entorno de desarrollo integrado (IDE) orientado al desarrollo frontend y aplicaciones JavaScript/TypeScript, que ofrece herramientas avanzadas para mejorar la productividad.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Angular</h4>Framework para el desarrollo de aplicaciones web modernas y escalables basado en el modelo Single Page Application (SPA), que facilita la creación de interfaces dinámicas mediante TypeScript.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>IntelliJ IDEA</h4>Entorno de desarrollo integrado (IDE) utilizado principalmente para el desarrollo en Java, que ofrece herramientas avanzadas para la codificación, depuración y pruebas.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Java</h4>Lenguaje de programación orientado a objetos utilizado para desarrollar aplicaciones robustas, seguras y multiplataforma.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Spring Boot</h4>Framework basado en Java que facilita el desarrollo de aplicaciones y microservicios robustos y escalables.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Swagger</h4>Herramienta utilizada para diseñar, documentar y probar APIs RESTful de manera interactiva.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Android Studio</h4>Entorno de desarrollo oficial para aplicaciones Android, que proporciona herramientas para programación, diseño de interfaces y pruebas.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Kotlin</h4>Lenguaje de programación moderno y conciso utilizado principalmente para el desarrollo de aplicaciones Android.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Gradle</h4>Herramienta de automatización de compilación y gestión de dependencias utilizada en proyectos Java y Android.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Jetpack Compose</h4>Toolkit moderno de Android para la creación de interfaces de usuario nativas mediante programación declarativa en Kotlin.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>MySQL Workbench</h4>Herramienta visual utilizada para el diseño, modelado y administración de bases de datos MySQL.</td>
  </tr>

  <tr>
    <td>Software Deployment</td>
    <td><h4>GitHub Pages</h4>Servicio de alojamiento web utilizado para realizar el despliegue y publicación del landing page del proyecto.</td>
  </tr>
</table>


### 4.1.2. Source Code Management ###

Hemos optado por crear un repositorio en GitHub para nuestro proyecto, tanto para el informe como para la landing page. Esto facilitó la colaboración entre los miembros del equipo,aprovechando las herramientas útiles que esta plataforma ofrece para el manejo del código fuente y sus versiones.

- URL del repositorio Report en GitHub: https://github.com/OpenSource-Grupo-4/ReportTB1
- URL del repositorio Landing Page en GitHub: https://github.com/OpenSource-Grupo-4/Landing-Page
- URL del repositorio de la Web Application en GitHub:https://github.com/OpenSource-Grupo-4/Frontend-WeRide
- URL del respositorio de los Web Services en GitHub:https://github.com/OpenSource-Grupo-4/Backend-WeRide

### 4.1.3. Source Code Style Guide & Conventions ###

##### Landing Page:

Para "**WeRide**", hemos utilizado "**HTML y CSS**". Para estructurar el contenido usamos etiquetas de section y divisiones para contenido específico de cada una de las secciones. Además, hemos empleado atributos como ***HTML Style*** para personalizar el aspecto visual, definiendo propiedades como color, tamaño de fuente y tipo de letra.

Para resaltar elementos importantes, hemos aplicado ***HTML Text Formatting***, incluyendo etiquetas como b para negrita, strong para resaltado y del para mostrar cambios de precios. En cuanto a la navegación, hemos implementado una barra de navegación horizontal utilizando **CSS** para mejorar la experiencia del usuario al explorar el contenido.

Los formularios, creados con **CSS**, permiten a los usuarios ingresar información relevante, como detalles de inicio de sesión, información de pago y dirección de envío. Para añadir interactividad, hemos agregado botones con efectos hover utilizando CSS y paginación CSS para facilitar la navegación entre las diferentes páginas de productos.

Finalmente, en el **footer**, hemos incluido enlaces a las redes sociales de la organización para brindar a los usuarios una forma adicional de conectarse y seguir nuestras actualizaciones.

##### Web Application:

Para "**WeRide Web**", hemos utilizado "**TypeScript, HTML y CSS**". La estructura del proyecto sigue el patrón de arquitectura de **Single Page Application (SPA)**, utilizando el framework **Angular** para organizar el código en módulos, componentes y servicios.

Los componentes estan estructurados según DDD (Domain-Driven Design), donde cada componente representa un bounded context específico, como **auth**, **booking**, **garage**, **plans** y **trip**. Cada componente tiene su propio archivo HTML para la estructura, CSS para el estilo y TypeScript para la lógica y enrutamiento así como la comunicación entre componentes y servicios.

##### Mobile Application:

Para "**WeRide Mobile**", se ha utilizado Kotlin junto con Jetpack Compose para el desarrollo nativo en Android. La estructura del proyecto sigue una arquitectura modular basada en buenas prácticas de desarrollo, separando la lógica de negocio, la interfaz de usuario y la gestión de datos para mejorar la mantenibilidad y escalabilidad de la aplicación.

Los componentes de la aplicación están organizados en paquetes según sus funcionalidades, como authentication, booking, profile, trip y plans. Cada pantalla se desarrolla mediante composables de Jetpack Compose, permitiendo construir interfaces dinámicas y reactivas de manera declarativa. Asimismo, se emplean ViewModels para la gestión del estado y la comunicación entre la interfaz y la lógica de negocio.

Siguiendo las convenciones de Kotlin, los nombres de paquetes se escriben en minúsculas y sin guiones bajos. Para clases y composables se utiliza la nomenclatura UpperCamelCase, mientras que las funciones, propiedades y variables locales emplean camelCase. Además, se prioriza el uso de val sobre var para fomentar la inmutabilidad y mantener un código más seguro y mantenible.

### 4.1.4. Software Deployment Configuration ###

##### Landing Page:

Utilizaremos GitHub Pages para alojar nuestra Landing Page. Para lograrlo, subiremos los archivos esenciales (HTML, CSS, etc.) a un repositorio público en GitHub. De
esta manera, nuestra página estará disponible en línea y accesible para todos los usuarios.

![GithubReportRepo](assets/chapter05/github-repo.png)

##### Web Application:

Utilizaremos Vercel para alojar nuestra Web Application.
Para lograrlo, configuraremos un proyecto en Vercel y conectaremos nuestro repositorio de GitHub. Vercel se encargará de la construcción y el despliegue de nuestra aplicación automáticamente cada vez que realicemos un push a la rama principal.


## _4.2. Landing Page & Mobile Applications Implementation_ ##

### 4.2.1. Sprint 1 ###

#### 4.2.1.1. Sprint Planning 1 ####

#### 4.2.1.2. Sprint Backlog 1 ####

#### 4.2.1.3. Development Evidence for Sprint Review 1 ####

#### 4.2.1.4. Testing Suite Evidence for Sprint Review 1 ####

#### 4.2.1.5. Execution Evidence for Sprint Review 1 ####

#### 4.2.1.6. Services Documentation Evidence for Sprint Review 1 ####

#### 4.2.1.7. Software Deployment Evidence for Sprint Review 1 ####

#### 4.2.1.8. Team Collaboration Insights during Sprint 1 ####

## _4.3. Entrevistas de validación_ ##

### 4.3.1. Diseño de entrevistas de validación ###

### 4.3.2. Registro de entrevistas de validación ###

### 4.3.3. Evaluaciones según heurísticas ###
