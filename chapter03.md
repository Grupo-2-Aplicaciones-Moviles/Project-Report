# Capitulo 3: Solution UI/UX Design #

## _3.1. Product Design_ ##

### 3.1.1. Style Guidelines ###

#### 3.1.1.1. General Style Guidelines ####

<h3>Branding</h3>

El logo de WR sintetiza de manera elegante y minimalista la propuesta de valor de la marca en el mundo de la micromovilidad electrica. El diseno en tipografia negra sobre fondo blanco comunica sobriedad, confianza y profesionalismo, asegurando legibilidad en cualquier soporte digital o fisico.

En la parte superior, el scooter electrico estilizado simboliza movimiento, innovacion y sostenibilidad, elementos centrales de la experiencia que WR ofrece. Su posicion por encima de las iniciales representa la prioridad de la movilidad sobre cualquier otra funcion, transmitiendo dinamismo y accion inmediata.

La composicion general mantiene un equilibrio entre modernidad y simplicidad, ideal para una plataforma tecnologica que busca conectar a las personas con alternativas de transporte accesibles, rapidas y ecologicas. La eleccion de una paleta monocromatica resalta la seriedad de la propuesta, mientras que el icono del scooter anade cercania y un toque aspiracional.

Con este logo, WR se presenta como una marca confiable, eficiente y enfocada en transformar el desplazamiento urbano, adaptandose a las necesidades de estudiantes, profesionales y empresas.

***Variantes de logo***

***Logo original***

![User Persona](assets/Chapter04/Logo1.png)

***Logo con iniciales light color***

![User Persona](assets/Chapter04/Logo3.png)

***Colores invertidos***

![User Persona](assets/Chapter04/Logo4.png)


<h3>Typography</h3>

La tipografia de nuestra app de micromovilidad electrica refleja dinamismo, innovacion y accesibilidad, alineandose con los valores de sostenibilidad y movilidad inteligente que representamos. Hemos elegido una fuente sans-serif moderna, limpia y ligera, que transmite agilidad y simplicidad, elementos esenciales de nuestro servicio.

La fuente principal sera "Kay Pho Du", que por su diseno esbelto y geometrico comunica tecnologia y orden sin perder cercania. Su alta legibilidad permite que los usuarios puedan consultar informacion rapida mientras se desplazan.

Para lograr una jerarquia visual clara, los titulos y subtitulos tendran un tamano mas prominente que el cuerpo del texto. Los titulos (H1, H2) enfatizan energia y movimiento, mientras que los textos secundarios mantienen un tono amigable y sencillo.

El cuerpo del texto usara un tamano base adaptable, que garantice lectura sin esfuerzo tanto en pantallas pequenas (smartphones) como en tablets. Se mantendra un interlineado aireado y margenes equilibrados para no saturar la interfaz.

El lenguaje sera directo y motivador, usando un tono casual que inspire confianza y fomente la adopcion de alternativas de transporte sostenible.

<h3>Colors</h3>

La paleta de colores de nuestra app de micromovilidad electrica fue disenada para reforzar el impacto visual del logo y proyectar dinamismo, sostenibilidad y confianza. El blanco se mantiene como base, representando simplicidad, limpieza y espacios abiertos, facilitando que los elementos clave destaquen sin saturar la vista.

El negro profundo del logo se utiliza en tipografia principal y elementos estructurales, comunicando seriedad y profesionalismo. Para transmitir energia y movimiento, incorporamos un verde lima brillante (#18FA3A) como color de acento, ideal para botones de accion (reservar, iniciar viaje) y mensajes de confirmacion. Este tono evoca sostenibilidad y vitalidad, conectando con la mision de promover transporte limpio.

Un gris color (#EEEEEE) complementa la paleta y refuerza la percepcion tecnologica de la plataforma, utilizado en iconos interactivos y estados activos. Ademas, tonos gris claro (#EAEAEA) y gris oscuro (#4F4F4F) equilibran la interfaz, mejorando la legibilidad y jerarquizando la informacion.

En conjunto, esta paleta crea una identidad moderna, agil y ecologica, que motiva a los usuarios a adoptar la movilidad electrica como su primera opcion dentro y fuera del campus.

---

#### Paleta de colores - WeRide

| **Color**        | **Uso**                                                                 | **Codigo Hex** |
|------------------|-------------------------------------------------------------------------|---------------|
| Blanco           | Fondo principal de la interfaz, espacios vacios, sensacion de limpieza y orden. | `#FFFFFF`     |
| Negro profundo   | Logo, textos principales, iconos y elementos estructurales.              | `#000000`     |
| Verde energia    | Botones de accion (reservar, iniciar viaje), confirmaciones y mensajes de exito. | `#18FA3A`     |
| Gris claro       | Fondos secundarios, separadores, tarjetas de informacion.                | `#D9D9D9`     |
| Gris medio       | Texto secundario, iconos inactivos, descripciones y estados deshabilitados. | `#A6A6A6`     |

### 3.1.2. Information Architecture ###

#### 3.1.2.1. Organization Systems ####

Para la **landing page** de WeRide, se ha optado por una estructura jerarquica para ambos segmentos de usuarios, ya que se cuenta con una barra de navegacion superior que dirige a diferentes secciones, cada una encapsulando informacion relevante y relacionada.

Para el proceso de inicio de sesion o creacion de cuenta, se utiliza una organizacion lineal, permitiendo que el usuario avance paso a paso a medida que completa los datos requeridos hasta finalizar el registro o acceso.

Dentro de la aplicacion principal, se mantiene una organizacion jerarquica para separar y encapsular las distintas funcionalidades, independientemente del tipo de usuario. Esto asegura que, aunque los usuarios tengan diferentes necesidades y accesos, ****la estructura de la aplicacion sea coherente y facil de navegar.****


#### 3.1.2.2. Labelling Systems ####

Las etiquetas emplean un lenguaje claro y conciso, alineado con el tono casual y motivador de la marca:
**Inicio:** Vista principal con mapa y scooters disponibles.
**Reservar:** Flujo de reserva paso a paso.
**Mis Viajes:** Historial de viajes y reservas activas.
**Perfil:** Gestion de cuenta, metodo de pago y preferencias.
**Ayuda:** Centro de soporte con preguntas frecuentes y contacto.

#### 3.1.2.3. SEO Tags and Meta Tags ####

**Titulo:**
```html
<title>WeRide</title>
```

**Codificacion de caracteres:**
```html
<meta charset="utf-8">
```

**Descripcion:**
```html
<meta name="description" content="WeRide is a mobile application focused on providing sustainable and smart urban mobility through electric scooters, bikes, and motorcycles.">
```

**Autor y Derechos de Autor:**
```html
<meta name="author" content="CultiConection">
<meta name="copyright" content="Copyright WeTech team" />
```

#### 3.1.2.4. Searching Systems ####

El sistema integral de micromovilidad electrica compartida incorporara un **modulo de busqueda y localizacion en tiempo real**, que permitira a los usuarios identificar la ubicacion disponible de los vehiculos mas cercanos (scooters, bicicletas y motos electricas). Este sistema se sustenta en las siguientes caracteristicas:

Geolocalizacion en tiempo real: Cada vehiculo estara equipado con dispositivos GPS e IoT que transmitiran su ubicacion de manera constante hacia la plataforma central.

**Mapa interactivo en la aplicacion movil**: La app mostrara en un mapa la ubicacion exacta de los vehiculos disponibles, diferenciados por tipo (scooter, bicicleta o moto electrica).

**Filtros de busqueda avanzada**: Los usuarios podran buscar vehiculos segun tipo de unidad preferida, nivel de bateria disponible y distancia a pie desde su ubicacion actual.

**Reserva inmediata**: Una vez identificado el vehiculo, el usuario podra seleccionarlo en la aplicacion, reservarlo y dirigirse a recogerlo.

**Optimizacion para empresas**: En el caso de suscripciones corporativas, los sistemas de busqueda tambien permitiran a los empleados visualizar vehiculos disponibles en zonas cercanas a sus oficinas o campus.

#### 3.1.2.5. Navigation Systems ####

El sistema integral de micromovilidad electrica compartida contara con un modulo de navegacion inteligente que facilitara al usuario el uso de los vehiculos y la planificacion de sus desplazamientos.

**Guia hacia el vehiculo seleccionado**: Una vez realizada la reserva, la aplicacion mostrara la ruta a pie mas rapida desde la ubicacion del usuario hasta el vehiculo disponible, mediante mapas integrados en tiempo real.

**Navegacion durante el viaje**: El sistema proporcionara indicaciones de ruta para que el usuario se desplace de manera eficiente hacia su destino, evitando zonas de alto trafico cuando sea posible. Se integran APIs de mapas inteligentes como Google Maps o Mapbox.

**Seguridad en la navegacion**: Alertas en la aplicacion respecto a calles restringidas, recomendacion de rutas seguras y opciones de personalizacion (ruta mas rapida, mas segura o mas ecologica).

**Gestion de estaciones y puntos de aparcamiento**: La navegacion incluira la localizacion de zonas de parqueo autorizadas, estaciones de carga o puntos estrategicos.


### 3.1.3. Landing Page UI Design ###

#### 3.1.3.1. Landing Page Wireframes ####

- Navbar  
![Navbar](assets/Chapter04/WireframeLandingPage/Navbar.png)
- Hero  
![Hero](assets/Chapter04/WireframeLandingPage/Hero.png)
- Disposable Vehicles Section.  
![Vehicles](assets/Chapter04/WireframeLandingPage/Disposables_Vehicles_Section.png)
- Application user manual section.  
![Manual](assets/Chapter04/WireframeLandingPage/Application_user_manual_section.png)
- Rates Section.  
![Rates](assets/Chapter04/WireframeLandingPage/Rates_Section.png)
- Locations section.  
![Locations](assets/Chapter04/WireframeLandingPage/Locations_Section.png)
- Who we are section.  
![Wo we are](assets/Chapter04/WireframeLandingPage/Who_we_are_Section.png)
- About section.  
![About](assets/Chapter04/WireframeLandingPage/About_Section.png)
- Application download section.  
![Download app](assets/Chapter04/WireframeLandingPage/Download_Section.png)
- Footer Section.  
![Footer](assets/Chapter04/WireframeLandingPage/Footer_Section.png)

#### 3.1.3.2. Landing Page Mock-ups ####

- Navbar  
![Navbar](assets/Chapter04/Mock-upLandingPage/Navbar_Section.png)
- Hero  
![Hero](assets/Chapter04/Mock-upLandingPage/Hero_Section.png)
- Disposable Vehicles Section.  
![Vehicles](assets/Chapter04/Mock-upLandingPage/Disposables_Vehicles_Section.png)
- Application user manual section.  
![Manual](assets/Chapter04/Mock-upLandingPage/Application_User_manual_Section.png)
- Rates Section.  
![Rates](assets/Chapter04/Mock-upLandingPage/Rates_Section.png)
- Locations section.  
![Locations](assets/Chapter04/Mock-upLandingPage/Locations_section.png)
- Who we are section.  
![Wo we are](assets/Chapter04/Mock-upLandingPage/Who_we_are_Section.png)
- About section.  
![About](assets/Chapter04/Mock-upLandingPage/About_section.png)
- Application download section.  
![Download app](assets/Chapter04/Mock-upLandingPage/Download_Section.png)
- Footer Section.  
![Footer](assets/Chapter04/Mock-upLandingPage/Footer_Section.png)

### 3.1.4. Mobile Applications UI/UX Design ###

#### 3.1.4.1. Mobile Applications Wireframes ####

- Login
En esta pantalla el usuario puede iniciar sesión en la aplicación mediante diferentes métodos de acceso, como Google, número de celular o correo empresarial. Esto permite un acceso rápido y seguro a las funcionalidades de la plataforma.

![Login](assets/chapter04/Login.png)

- Numero Celular
En esta pantalla el usuario debe ingresar su número de celular para continuar con el proceso de autenticación. Posteriormente, recibirá un código de verificación que permitirá validar su identidad y acceder a la aplicación.

![Numero](assets/chapter04/Numero.png)

![Codigo](assets/chapter04/Codigo.png)

- Datos
Esta interfaz permite al usuario registrar sus datos personales, como nombres y apellidos. La información ingresada será utilizada para crear y personalizar su cuenta dentro de la aplicación.

![Datos](assets/chapter04/Datos.png)

- Principal
En esta seccion el usuario puede visualizar las opciones de movilidad disponibles, como motos eléctricas, scooters y bicicletas eléctricas. Además, se muestra información básica de cada vehículo, como el rango estimado, y botones para conducir o reservar, facilitando la selección rápida del medio de transporte deseado.

![Principal1](assets/chapter04/Principal1.png)

![Principal2](assets/chapter04/Principal2.png)

![Principal3](assets/chapter04/Principal3.png)

- Perfil.
En esta pantalla el usuario puede acceder a la información y configuraciones de su cuenta. Además, cuenta con opciones como cartera, historial, centro de seguridad, ayuda y ajustes, permitiendo gestionar de manera rápida distintos aspectos de la aplicación.

![Perfil](assets/chapter04/Perfil.png)

- Garaje.
En esta sección se muestran los vehículos disponibles, organizados por categorías como scooters, motos y bicicletas. Cada tarjeta presenta información básica del producto, permitiendo al usuario explorar y seleccionar opciones de movilidad.
  
![Garaje](assets/chapter04/Garaje.png)

- Planes.
Esta pantalla muestra los diferentes tipos de planes disponibles dentro de la aplicación, como normal, estudiantil y empresarial. El usuario puede seleccionar el plan que mejor se adapte a sus necesidades para acceder a beneficios específicos.

![Planes](assets/chapter04/Planes.png)

- Tarifas.
En esta pantalla se muestran los distintos pases o tarifas disponibles dentro de la aplicación. Cada opción incluye una breve descripción de sus beneficios, como viajes ilimitados durante un periodo determinado, además de un botón de pago para adquirir el plan seleccionado.

![Tarifas](assets/chapter04/Tarifas.png)

- Pago.
En esta pantalla el usuario puede realizar el pago del servicio o plan seleccionado. Además, permite visualizar el monto a pagar, seleccionar un método de pago y confirmar la transacción de manera rápida y segura.

![Pago](assets/chapter04/Pago.png)

- Reserva.
En esta pantalla se muestra una animación que indica que la reserva fue realizada exitosamente. Su objetivo es brindar una confirmación visual rápida al usuario sobre la finalización correcta del proceso.

![Reserva](assets/chapter04/Reserva.png)


#### 3.1.4.2. Mobile Applications Wireflow Diagrams ####

##### Wireflow 1 — Registro e inicio de sesion

Este wireflow representa el proceso de acceso del usuario a la aplicación. Incluye las etapas de inicio de sesión, validación mediante número celular o correo, verificación de código e ingreso de datos personales para completar la autenticación.

![1](assets/chapter04/sesion.png)

##### Wireflow 2 — Suscripcion a planes

Este wireflow representa el proceso de selección y adquisición de planes o pases disponibles en la aplicación. El usuario puede visualizar las opciones, realizar el pago y confirmar la activación del plan seleccionado.


![2](assets/chapter04/planessus.png)

##### Wireflow 3 — Exploración de vehículos

Este wireflow muestra cómo el usuario puede explorar los distintos medios de transporte disponibles en la aplicación, como scooters, motos y bicicletas, permitiendo visualizar información básica antes de realizar una reserva.


![3](assets/chapter04/exp.png)

##### Wireflow 4 — Reserva de vehiculo

Este wireflow muestra el proceso que sigue el usuario para reservar un vehículo dentro de la aplicación. Inicia desde la pantalla principal, continúa con la selección del vehículo y la tarifa, y finaliza con el pago y la confirmación de la reserva.

![4](assets/chapter04/reserva.png)


#### 3.1.4.3. Mobile Applications Mock-ups ####

Los mock-ups de la aplicacion movil **WeRide** representan el diseno de alta fidelidad de cada pantalla, aplicando el Style Guide definido: paleta monocromatica con verde energia (`#18FA3A`) como acento, tipografia *Kay Pho Du*, fondo blanco y elementos estructurales en negro. A continuacion se presentan los mock-ups organizados por flujo funcional.

---

##### Flujo 1 — Acceso a la aplicacion (EP01)

**Pantalla de Bienvenida / Splash Screen**

La pantalla inicial muestra el logo de WeRide centrado sobre fondo negro, con el icono del scooter y el nombre de la marca. Refuerza el branding antes de redirigir al inicio de sesion.

![Splash Screen](assets/chapter03/01_splash_screen.png)

---

**Pantalla de Registro / Inicio de Sesion (US-01)**

Vista dividida en dos pestanas superiores: *Iniciar Sesion* y *Registrarse*. El formulario de login solicita correo electronico y contrasena. El boton de accion principal (color `#18FA3A`) activa la autenticacion. Se incluye la opcion de acceso con Google.

![Login & Register](assets/chapter03/02_login_register.png)

---

**Pantalla de Ingreso de Numero de Celular (US-02)**

Pantalla de paso unico con indicador de progreso de 3 pasos. Campo de numero telefonico con prefijo de pais (+51 Peru) autodetectado. El boton *Continuar* se activa en verde al cumplir el formato (9 digitos).

![Phone Number](assets/chapter03/03_phone_number.png)

---

**Pantalla de Verificacion de Codigo SMS (US-03)**

Seis campos de entrada numerica individuales centrados en pantalla. Contador de reenvio en gris. Al completar el codigo correcto, la pantalla transiciona automaticamente con confirmacion visual en verde.

![Verification Code](assets/chapter03/04_verification_code.png)

---

**Pantalla de Datos de Perfil (US-04)**

Formulario de creacion de perfil con campo de foto (circular con icono de camara), nombre completo, fecha de nacimiento y genero. Boton *Guardar y Continuar* en verde al pie de la pantalla.

![Profile Setup](assets/chapter03/05_profile_setup.png)

---

##### Flujo 2 — Funcionalidades principales (EP02)

**Pantalla Principal / Home (US-05)**

Vista central con mapa interactivo (Google Maps / Mapbox) mostrando vehiculos disponibles en tiempo real. Barra de busqueda de direccion en la parte superior. Bottom navigation bar con iconos de *Inicio*, *Garaje*, *Viaje*, *Planes* y *Tu*. Tarjeta flotante deslizable con el vehiculo mas cercano y boton *Reservar ahora* en verde.

![Home / Map](assets/chapter03/06_home_map.png)

---

**Pantalla de Perfil (US-06)**

Cabecera con foto y nombre del usuario sobre fondo negro. Lista de opciones: *Administrar cuenta*, *Personalizar perfil*, *Cartera*, *Mis Viajes*, *Centro de Seguridad*, *Ayuda* y *Ajustes*. Cada opcion tiene icono a la izquierda y flecha de navegacion a la derecha.

![Profile Screen](assets/chapter03/07_profile_screen.png)

---

**Pantalla de Garaje — Listado de Vehiculos (US-07)**

Catalogo con tarjetas de cada vehiculo: imagen, nombre, tipo, nivel de bateria en barra de progreso, calificacion en estrellas, disponibilidad y icono de favoritos. Chips de filtro por tipo en la parte superior.

![Garage List](assets/chapter03/08_garage_list.png)

---

**Pantalla de Garaje — Filtros (US-08)**

Bottom sheet deslizable con chips de seleccion para: tipo de vehiculo, nivel de bateria (slider), disponibilidad y calificacion minima. Boton *Aplicar filtros* en verde al pie.

![Garage Filter](assets/chapter03/09_garage_filter.png)

---

##### Flujo 3 — Gestion de pagos y suscripciones (EP03)

**Pantalla de Planes (US-09)**

Tres tarjetas de plan: *Basico*, *Estandar* y *Premium*. Cada tarjeta contiene precio mensual en soles, lista de beneficios con checks en verde y boton *Seleccionar*. El plan recomendado lleva etiqueta *POPULAR* con fondo verde.

![Plans Screen](assets/chapter03/10_plans_screen.png)

---

**Pantalla de Pago (US-10)**

Formulario con tres metodos: *Tarjeta* (numero, vencimiento y CVV), *Yape* (numero de celular + QR) y *Plin* (numero de celular). Pestanas superiores para cambiar metodo. Resumen de compra fijo al pie con boton *Finalizar Pago* en verde e icono de seguridad SSL.

![Payment Screen](assets/chapter03/11_payment_screen.png)

---

##### Flujo 4 — Mapa y localizacion (EP04)

**Pantalla de Mapa — Vehiculos Cercanos (US-11)**

Vista de mapa a pantalla completa con marcadores de vehiculos agrupados. Al tocar un vehiculo aparece tarjeta inferior con bateria, distancia y boton *Reservar* en verde. Leyenda de colores por tipo de vehiculo.

![Map Nearby](assets/chapter03/12_map_nearby_vehicles.png)

---

##### Flujo 5 — Gestion de viajes (EP05)

**Pantalla de Viaje Activo (US-12)**

Mapa con ruta trazada. Panel inferior con nivel de bateria animado, tiempo transcurrido, distancia recorrida y velocidad. Boton *Finalizar Viaje* en rojo y boton secundario *Reportar problema*.

![Active Trip](assets/chapter03/13_active_trip.png)

---

**Pantalla de Historial de Viajes (US-13)**

Lista cronologica de viajes en tarjetas con: fecha, tipo de vehiculo, distancia, duracion, costo y calificacion. Filtro por mes en la parte superior.

![Trip History](assets/chapter03/14_trip_history.png)

---

**Pantalla de Calificacion de Viaje (US-14)**

Modal post-viaje con resumen del trayecto y 5 estrellas interactivas. Campo opcional de comentario. Boton *Enviar Calificacion* (verde) y *Omitir* (gris). Animacion de confirmacion con check verde al enviar.

![Trip Rating](assets/chapter03/15_trip_rating.png)

---

**Pantalla de Reporte de Problema (US-15)**

Chips de categoria: *Falla mecanica*, *Bateria*, *Bloqueo*, *Accidente*, *App*. Campo de descripcion de texto libre y opcion de adjuntar foto. Confirmacion con numero de ticket asignado.

![Report Problem](assets/chapter03/16_report_problem.png)

---

##### Flujo 6 — Gestion de reservas (EP06)

**Pantalla de Detalle de Vehiculo y Creacion de Reserva (US-17)**

Imagen grande del vehiculo, nombre, tipo, modelo y nivel de bateria. Seccion de informacion con ubicacion exacta (mapa miniatura) y estacion virtual. Boton *Reservar ahora* en verde. Al confirmarse, contador regresivo de reserva activa.

![Vehicle Detail & Reserve](assets/chapter03/17_vehicle_detail_reserve.png)

---

**Pantalla de Reserva Activa con Notificacion (US-16, US-18)**

Temporizador circular de cuenta regresiva en verde, distancia y direccion al vehiculo, boton *Cancelar Reserva* y boton *Desbloquear Vehiculo*. Notificacion push visible cuando faltan 2 minutos para la expiracion.

![Active Reservation](assets/chapter03/18_active_reservation.png)

---

##### Flujo 7 — Desbloqueo de vehiculos (EP07)

**Pantalla de Desbloqueo por QR (US-19)**

Visor de camara con marco de escaneo animado en verde. Instruccion: *"Apunta al codigo QR del vehiculo"*. Al escanear: animacion de desbloqueo y mensaje *"Vehiculo desbloqueado!"* en verde. En error: mensaje en rojo con opcion de reintentar.

![QR Unlock](assets/chapter03/19_qr_unlock.png)

---

**Pantalla de Desbloqueo desde la App (US-20, US-21)**

Estado en tiempo real del desbloqueo con icono de candado animado (cerrado → abriendo → abierto). Tres estados: *Procesando...* (gris), *Desbloqueando...* (amarillo) y *Desbloqueado!* (verde). Transicion automatica a Viaje Activo al confirmarse.

![App Unlock](assets/chapter03/20_app_unlock_status.png)

---

**Pantalla de Desbloqueo Programado (US-22)**

Selector de fecha y hora nativo de Android. Listado de vehiculos disponibles en ese horario con indicador de disponibilidad. Boton *Confirmar Programacion* y opcion de agregar al calendario del dispositivo.

![Scheduled Unlock](assets/chapter03/21_scheduled_unlock.png)

---

#### 3.1.4.4. Mobile Applications Userflow Diagrams ####

Los diagramas de flujo de usuario representan los caminos que recorre el usuario dentro de la aplicacion movil para completar una tarea especifica, mostrando cada pantalla, decision y transicion. Se presentan los cinco flujos mas representativos de WeRide, alineados con los Bounded Contexts y User Stories del Capitulo 2.

---

##### Userflow 1 — Registro e Inicio de Sesion (US-01, US-02, US-03, US-04)

Este flujo cubre el acceso completo a la aplicacion, desde la apertura hasta el acceso al Home. Inicia en el Splash Screen y bifurca segun si el usuario ya tiene cuenta. El flujo de registro incluye validacion de numero de celular mediante codigo SMS y creacion de perfil. El flujo de login valida credenciales con mensaje de error en caso de fallo.

**Pantallas:** Splash → Login/Registro → Nro. Celular → Codigo SMS → Datos de Perfil → Home.

![Userflow 1 - Registro e Inicio de Sesion](assets/chapter03/userflow_01_registro_login.png)

---

##### Userflow 2 — Busqueda, Reserva y Desbloqueo de Vehiculo (US-11, US-17, US-19, US-20, US-21)

Flujo principal de uso: desde localizar un vehiculo hasta iniciar el viaje. Incluye verificacion de plan activo (derivando a seleccion de plan si no tiene) y bifurcacion entre desbloqueo por QR o desde la app, con manejo de errores en ambos casos.

**Pantallas:** Home → Mapa → Detalle Vehiculo → (Planes → Pago →) Reserva Activa → QR/Desbloqueo → Viaje Activo.

![Userflow 2 - Reserva y Desbloqueo](assets/chapter03/userflow_02_reserva_desbloqueo.png)

---

##### Userflow 3 — Viaje Activo, Finalizacion y Calificacion (US-12, US-13, US-14, US-15)

Flujo de la experiencia de viaje desde el inicio hasta la retroalimentacion post-trayecto. Incluye la opcion de reporte de problema durante el viaje y el flujo completo de calificacion con comentario opcional, finalizando con la generacion automatica de factura.

**Pantallas:** Viaje Activo → (Reporte Problema →) Finalizar → Resumen → Rating → Factura → Home.

![Userflow 3 - Viaje y Calificacion](assets/chapter03/userflow_03_viaje_calificacion.png)

---

##### Userflow 4 — Seleccion y Pago de Plan (US-09, US-10)

Flujo de contratacion de plan de suscripcion. El usuario navega entre los tres planes, selecciona el metodo de pago (Tarjeta, Yape o Plin), revisa el resumen y confirma. Incluye manejo del error de pago con opcion de reintento.

**Pantallas:** Planes → Detalle Plan → Pago → Resumen → Confirmacion → Home.

![Userflow 4 - Seleccion de Plan](assets/chapter03/userflow_04_planes_pago.png)

---

##### Userflow 5 — Desbloqueo Programado (US-22)

Flujo para usuarios que planifican su viaje con anticipacion. Permite seleccionar fecha y hora, verificar disponibilidad del vehiculo en ese horario, confirmar la programacion y recibir notificacion automatica en el momento indicado para el desbloqueo.

**Pantallas:** Garaje → Detalle Vehiculo → Programar Desbloqueo → Confirmacion → (Notificacion automatica) → Viaje Activo.

![Userflow 5 - Desbloqueo Programado](assets/chapter03/userflow_05_desbloqueo_programado.png)

---

#### 3.1.4.5. Mobile Applications Prototyping ####

El prototipo interactivo de la aplicacion movil **WeRide** fue desarrollado en **Figma**, herramienta seleccionada por el equipo para el diseno colaborativo de interfaces. El prototipo conecta todos los mock-ups de alta fidelidad mediante transiciones y animaciones que simulan la experiencia real de uso en un dispositivo Android, utilizando el frame **Android Large (360 x 800 px)**.

---

##### Descripcion del prototipo

El prototipo cubre los **cinco flujos principales** de la aplicacion (registro, reserva, viaje, planes y desbloqueo programado), permitiendo navegar entre pantallas mediante interacciones tactiles simuladas: tap, swipe, long press y scroll. Las transiciones empleadas son *Smart Animate* para cambios de estado fluidos y *Slide* para la navegacion entre vistas principales.

**Caracteristicas tecnicas del prototipo:**

| Parametro | Detalle |
|---|---|
| Herramienta | Figma (Prototype mode) |
| Frame base | Android Large — 360 x 800 px |
| Cantidad de pantallas | 21 pantallas de alta fidelidad |
| Flujos cubiertos | 5 flujos principales (US-01 a US-22) |
| Tipo de transiciones | Smart Animate, Slide, Dissolve |
| Hotspots activos | Botones CTA, iconos de navegacion, campos de formulario, QR scanner simulado |

---

##### Flujo 1 — Acceso a la aplicacion (Splash → Login → Verificacion → Perfil → Home)

Desde el Splash Screen, el usuario elige entre registrarse o iniciar sesion. El prototipo simula la validacion del codigo SMS y la transicion al formulario de perfil hasta llegar al Home.

![Prototipo Flujo 1 - Acceso](assets/chapter03/prototype_flow_01_acceso.png)

---

##### Flujo 2 — Reserva y Desbloqueo (Home → Mapa → Reserva → QR → Viaje Activo)

El mapa interactivo permite seleccionar un vehiculo y acceder a su detalle. El boton *Reservar ahora* activa el temporizador animado de 15 minutos y habilita las opciones de desbloqueo.

![Prototipo Flujo 2 - Reserva y Desbloqueo](assets/chapter03/prototype_flow_02_reserva_desbloqueo.png)

---

##### Flujo 3 — Viaje Activo y Calificacion

Simula el estado de viaje en tiempo real con mapa de ruta trazado. El boton *Finalizar Viaje* activa el flujo de resumen, calificacion y generacion de factura simulada.

![Prototipo Flujo 3 - Viaje y Calificacion](assets/chapter03/prototype_flow_03_viaje_rating.png)

---

##### Flujo 4 — Seleccion de Plan y Pago

Permite navegar entre los tres planes y simula el proceso de pago con los tres metodos (tarjeta, Yape y Plin), mostrando el estado de aprobacion y el mensaje de plan activado.

![Prototipo Flujo 4 - Planes y Pago](assets/chapter03/prototype_flow_04_planes_pago.png)

---

##### Vista general del prototipo en Figma

![Vista general Figma](assets/chapter03/prototype_figma_overview.png)

---

##### Decisiones de diseno del prototipo

Durante el proceso de prototipado, el equipo tomo las siguientes decisiones de diseno basadas en los hallazgos de las entrevistas del Capitulo 2:

- **CTAs siempre visibles:** Los botones de accion principal (*Reservar*, *Desbloquear*, *Pagar*) estan siempre en la zona de alcance del pulgar (bottom 30% de la pantalla), respondiendo al feedback sobre botones poco visibles identificado en las entrevistas.

- **Precios siempre visibles:** Los costos del plan y de la reserva se muestran en cada etapa del flujo sin necesidad de navegar a otra pantalla, eliminando la friccion identificada en las entrevistas con Gianella Castro.

- **Integracion de Yape/Plin en primer plano:** Los metodos de pago locales aparecen como primera opcion en la pantalla de pago, alineandose con el comportamiento de pago de los usuarios peruanos entrevistados que prefieren Yape sobre tarjeta.

- **Onboarding progresivo:** El registro se divide en 3 pasos cortos (celular → verificacion → perfil) en lugar de un formulario extenso, reduciendo la friccion de adopcion inicial identificada en el segmento B2C.

- **Bottom Navigation fija:** La barra de navegacion inferior se mantiene presente en todas las pantallas principales, garantizando acceso inmediato a las cinco secciones clave sin importar la profundidad de navegacion.
