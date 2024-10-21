<h2 align="center">Escenario Dental</h2>

###

<p align="justify"><span>Nombre: </span>Sistema de Gestion de Consultas Dentales</p>

<p align="justify"><span>Problematica: </span>
    En el Hospital Dental se requiere de un sistema web para la programación y organización de la agenda de los médicos que ahí laboran, así como para las consultas y citas de sus pacientes.
</p>

<p align="justify"><span>Descripción: </span>
    El control que se realiza actualmente en el hospital es de forma manual, registrando las diversas actividades en un cuaderno, 
    situación que representan un problema dado que se duplican las citas y no se tiene un control adecuado de las fechas y horas de atención.
    Para superar esta problemática, se requiere de una agenda electrónica personalizada que cubra estas necesidades. 
    Lo que debe contener dicha agenda son los datos personales del paciente como son: 
</p>

<ol>
    <li>Usuario</li>
    <li>Constraseña</li>
    <li>Nombre y Apellidos</li>
    <li>Teléfono</li>
    <li>Dirección</li>
</ol>

<p align="justify">
    Estos elementos permitirán conformar un banco de datos con la información básica del paciente, 
    lo que facilitara el acceso a ellos cuando algún médico lo requiera o cuando sea necesario programar alguna consulta, 
    sin tener la necesidad de registrar nuevamente sus datos. Quien lleva la aprobación de los datos de los pacientes es la secretaria: 
    ella es la responsable de canalizarlos la primera vez, ya que, una vez aprobados en el sistema, ellos tendrán la posibilidad de programar sus propias citas. 
</p>

<p align="justify">
    La agenda deberá contener citas y consultas: las citas podrán solicitarse por los pacientes y su duración es de 30 minutos, 
    manejando un horario de 10:00 a 13:00 hrs, mientras que las consultas únicamente las podrán agendar los médicos, y están tendrán una duración de una hora, 
    dentro de un horario de 15:00 a 19:00 hrs. La consulta durara dependiendo de la complejidad del trabajo. 
</p>

<p align="justify">
    Los pacientes podrán programar sus citas vía internet y con ello ahorrar tiempo en cada visita. El sistema tendrá diferentes sesiones con distintos privilegios, 
    una para los médicos, otra para el administrador y una mas para los pacientes, de modo que se puedan autentificar por medio de un usuario y una contraseña.
    Los servicios que se brindaran en el Hospital Dental son:
</p>

<ol>
    <li>Limpieza Dental</li>
    <li>Colocacion y Cambio de Amalgama</li>
    <li>Colocacion y Cambio de Resina</li>
    <li>Extraccion de Piezas Dentales</li>
</ol>

<p align="justify">
    La agenda debe evitar errores en el registro de las citas y consultas, por ejemplo: programar a la misma hora y en la misma fecha, y permitir citas los domingos. 
    La secretaria (administrador del sistema) podrá registrar, editar, borrar y consultas los datos de los médicos, los cuales deben tener un usuario, contraseña, nombre, apellidos y especialidad.
</p>

<p align="justify">
    Los médicos consultarán su agenda por fecha determinada, las citas y consultas que tengan asignadas cada uno de los pacientes, así como la hora previamente programada. 
    Un requisito es que cada uno de los usuarios deben autentificarse en el sistema para tener acceso. 
</p>

<p align="justify">
    La interfaz gráfica del sistema web debe ser fácil de usar, amigable y funcional para el usuario. 
</p>

<p align="justify">
    Como prioridad, los datos de los pacientes deben ser confidenciales, ya que es una política del hospital, por lo que se requieren implementar algún mecanismo de seguridad, 
    en este caso utilizaremos la autentificación de los usuarios.
</p>