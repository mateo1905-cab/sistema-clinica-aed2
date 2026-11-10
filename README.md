# sistema-clinica-aed2
Integrantes: Pablo Mateo Aramayo. Diego Altamirano.

Proyecto Integrador AED2 - SISTEMA CLÍNICA. Tema 8 - Sets, Queues y Stacks.

Desarrollaremos un sistema de gestión para una clínica médica desarrollado en Java. Usaremos el editor Eclipse. GitHub para registrar todos los cambios y poder compartir el proyecto. Trello, para trabajar en equipo, repartir tareas, organizar el trabajo en un tablero Kanban, con tres columnas simples (Por hacer, En proceso, Hecho)
Gestionaremos Urgencias por prioridad (Cola de prioridad/PriorityQueue): Los pacientes no se atenderán solo por orden de llegada. El programa asignará un nivel de gravedad (Rojo = Crítico, Amarillo = Intermedio, Verde = Leve). El sistema siempre extraerá automáticamente al paciente más grave primero, sin importar cuando haya llegado.

Administrar una Cola de Espera Normal (Cola/Queue): Para las consultas generales o trámites que no sean emergencias, los pacientes se atenderán por orden de llegada.

Deshacer Acciones en el Historial (Pila/Stack): Si el médico comete un error al registrar un diagnóstico, añadir un síntoma o modificar el historial clínico, el programa tendrá un botón de Deshacer. Al usarlo, el sistema eliminará la última modificación y regresará el historial al estado exacto en el que estaba antes.
