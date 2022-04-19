# Spotifiuby

## Guía de usuario de la app

El Usuario entra por primera vez a la aplicación, desde aquí puede navegar por las distintas opciones que tiene para poder registrar y/o iniciar sesión:

![alt text](media/HomeAuthScreen.png)

El Usuario primero necesita primero registrarse: oprime 'registrarse' e ingresa todos los datos solicitados por la aplicación:

![alt text](media/SignUpScreen1.png)
![alt text](media/SignUpScreen2.png)

Luego de ingresar sus datos el usuario recibe un mensaje por Whatsapp donde se indica cual es su PIN de validación de usuario:

![alt text](media/PINScreen.png)

Si el Usuario se registró como 'Artista' entonces será redireccionado a la pantalla de iniciar sesión, si entra como 'Listener' entonces se le solicitará una ubicación y que seleccione sus intereses musicales, luego sera redireccionado a la pantalla de inicio de sesión:

![alt text](media/RequestMusicalPreferencesScreen.png)

Si el Usuario ya se registro de manera exitosa entonces puede ir a 'iniciar sesión y ingresar con sus datos. Aqui el Usuario puede ingresar con una cuenta de Google o con sus datos Biometricos si lo prefiere:

![alt text](media/SignInScreen.png)

Si el Usuario ingresa de manera externa por primera vez entonces debera seleccinar si desea entrar como 'Artista' o 'Listener':

![alt text](media/RequestUserTypeToExternalUser.png)

Si en algun momento el Usuario olvida su contraseña entonces puede seleccionar una nueva con la pantalla de '¿Olvido su Contraseña?'

![alt text](media/ForgotPasswordScreen.png)

## Guía de usuario del backoffice

## Bitacora del proyecto

### Semana del 20/2/2022
- Se adecuó la arquitectura utilizada en Técnicas de Diseño, con el stack de React, Node, Express y PostgreSQL (con Sequelize como ORM). Al tener un conocimiento básico de este stack, esto puede permitir ahorrar mucho tiempo, y se entiende que tiene más soporte en términos de documentación online para el desarrollo de aplicaciones web que uno con backend en Python debido a su mayor difusión. Por otra parte, usar React Native tiene mútiples similitudes a React, con lo cual es el complemento natural para las tecnologías ya conocidas.
- Se logra una comunicación básica entre los dos repositorios ahora existentes.
- Se plantea una forma básica de lograr el "registro de un usuario", integrando Firebase.

### Semana del 27/2/2022
- Se refina el prototipo de registro de usuario.
- Se logró un despliegue exitoso en Heroku, separando los recursos de desarrollo de los productivos. 
- Se planteó una forma de gestionar los archivos de ambiente, de manera que al hacer un despliegue productivo se utilicen los hosts de Heroku.

### Semana del 6/3/2022
- Se logró un sistema adhoc para impactar los cambios en la base de datos al hacer un despliegue productivo.
- Se integró el resultado de las pruebas con Insmbul y Coveralls.

### Semana del 14/3/2022
- Integración preliminar de Datadog.
- Login preliminar con datos biométricos y cuenta externa para usuarios, y con correo electrónico para admin.
- Inicio preliminar de la parte de pagos.

### Semana del 21/3/2022
- Primer dashboard en datadog.
- Despliegue exitoso de sign in, sign up y forgot password para backoffice.
- Despliegue exitoso de sign in, sign up y forgot password para mobile.
- Integración preliminar con datadog para el seguimiento de requests.

### Semana del 27/3/2022
- Inicio del gateway de apis.
- Primera pantalla de administrador con listado, filtros y alta (de servicios/api-keys). 
- Endpoint de crear wallet listo en servicio de pagos.

### Semana del 3/4/2022
- Integración con servicios desde el backoffice.
- Despliegue dockerizado.
- Endpoints de payments.

### Semana del 10/4/2022
- Integración con Twilio.
- Capa de datos del repositorio con la información del contenido.
- Avance del Gateway en Python.

### Semana del 17/4/2022

### Semana del 24/4/2022

## Postmortem del Proyecto
