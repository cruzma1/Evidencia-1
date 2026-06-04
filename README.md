# Evidencia-1
Desarrollo de Evidencia 1 Materia de Computación en Java

/// NOTA IMPORTANTE
/// USUARIO UNIVERSAL APP: clinica
/// CONTRASENA: 123


~~ Software de gestión de citas para consultorio médico ~~

Esta aplicación de consola construida en Java simula la operación interna de una clínica, permitiendo restringir el acceso mediante credenciales de administrador, dar de alta al personal médico, pacientes y coordinar la programación de consultas médicas.


Configuración e Instalación

Para montar y ejecutar este sistema de forma local, sigue las siguientes pautas:

Requisitos 
Entorno de ejecución: Java Development Kit (JDK) 11.
Entorno de Desarrollo (IDE): IntelliJ IDEA 
Control de Versiones: Cuenta y herramientas de GitHub instaladas.


Instrucciones de Despliegue:
1. Montaje en el IDE: Inicia IntelliJ IDEA y dirígete a `File > New > Project` para estructurar tu espacio de trabajo. 
2. Estructura del Código: Descarga los archivos desde GitHub e integra el bloque principal en la clase ejecutable (`Main`). Posteriormente, genera las clases complementarias correspondientes a `Persona`, `Doctor`, `Paciente` y `Cita` dentro del proyecto.


Operación del Sistema
Validación de Identidad (Login)
Para ingresar a las funciones administrativas del consultorio, el sistema requiere estrictamente las siguientes credenciales de acceso:
Identificador: “clinica”
Clave de seguridad: ”123”

Opciones Disponibles en el Menú
Al autenticarse, el usuario puede interactuar con el sistema digitando el número de la acción que requiera:

1.  Alta Doctor: Registra en la base de datos a un nuevo médico recopilando su clave identificadora, nombre y su especialidad.
2. Alta Paciente: Añade pacientes ingresando sus datos generales (ID único y nombre).
3. Crear Cita: Vincula de forma lógica a un médico y a un paciente mediante sus identificadores, programando el día, la hora y el motivo.
4. Mostrar Citas: Genera un listado completo en la terminal que muestra todas las citas activas y la información de los involucrados.
5. Guardar y salir: Guarda la información almacenada en el código hacia los archivos físicos .csv localizados dentro del directorio db/ antes de concluir el proceso.


Créditos 

Este desarrollo forma parte de las evidencia entregable 1 para la asignatura de computación en Java.

Desarrollador: Manuel Cruz
Perfil: Alumno de Ingeniería en Computación Administrativa
Instituto: Universidad Tecmilenio
