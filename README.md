# sistema-gimnasio-aed2
Grupo 1
Integrantes: Pablo Mateo Aramayo. Diego Altamirano. Alan Joel Pires.

Proyecto Integrador AED2 - SISTEMA GIMNASIO. Tema 10 - Archivo de texto y CSV.

Desarrollaremos un sistema de gestión para un gimnasio desarrollado en Java. Usaremos el editor Eclipse. GitHub para registrar todos los cambios y poder compartir el proyecto. Trello, para trabajar en equipo, repartir tareas, organizar el trabajo en un tablero Kanban, con tres columnas simples (Por hacer, En proceso, Hecho). El proyecto se gestionará con Maven para integrar librerías externas de manejo de datos.

Problema: El gimnasio lleva el control de socios, pagos y asistencias en cuadernos de papel o planillas sueltas. Esto provoca perdida de información, dificultad para saber quien tiene la cuota vencida, desorden en el ingreso en horas pico y errores humanos al cargar datos que luego no se pueden revertir fácilmente.

Gestionaremos la persistencia de socios en Archivo de texto: El sistema permitirá registrar a los miembros del gimnasio (datos personales, tipo de membresía y estado de cuota) y guardar toda esta información de forma permanente en el disco mediante lectura y escritura de archivos de texto plano, asegurando que los registros no se pierdan al cerrar el programa.
Exportación de Registros a forma CSV: Utilizando la librería OpenCSV, el programa generará reportes estructurados exportando la base de datos de los socios y sus asistencias a un archivo CSV, permitiendo abrir y visualizar fácilmente los datos en hojas de cálculo. 
Importación de Datos: El sistema también permitirá cargar registros previos desde archivos externos para restaurar o actualizar la base de datos de socios.
Administrar una Cola de Espera: Para la atención en recepción, ingreso al gimnasio o consultas administrativas, los socios se atenderán por estricto, por orden de llegada.
Deshacer Acciones en el Historial: Si el recepcionista o administrador comete un error al registrar un socio, cargar un pago o modificar una asistencia, el programa contará con una función de "Deshacer" que eliminará la última modificación y regresará el sistema a su estado anterior.
