# Notas – Modelado BPMN Caso Base (Clínica Salud Viva)

## Descripción general

Durante la clase se modeló el proceso de agendamiento de citas médicas de la Clínica Salud Viva utilizando la notación BPMN. El objetivo fue representar gráficamente el flujo del proceso, identificando los actores involucrados, las actividades realizadas, los puntos de decisión y la interacción con el sistema.

Inicialmente, analizamos el contexto del caso base y definimos que el proceso comienza cuando el paciente accede al sistema de citas en línea y finaliza cuando el sistema guarda y agenda la cita correctamente en la base de datos.

## Identificación de actores y estructura

Se identificaron dos actores principales dentro del proceso:

* **Paciente**, quien realiza la solicitud de la cita y selecciona la información necesaria.
* **Sistema**, que valida la información ingresada y registra la cita.

Para representar esto, se utilizaron lanes que permitieron separar claramente las actividades realizadas por el paciente y las ejecutadas por el sistema.

## Actividades principales del proceso

El flujo inicia cuando el paciente accede al sistema y selecciona la especialidad médica. Posteriormente, el sistema verifica si la especialidad existe en la base de datos. Si existe, el paciente puede consultar y seleccionar un médico disponible, seguido de la validación correspondiente por parte del sistema.

Luego, el paciente selecciona el centro médico, la fecha y la hora de la cita, y el sistema verifica la disponibilidad de esta información. Una vez validada, el sistema genera un resumen de la cita, el cual es revisado por el paciente.

Finalmente, si los datos son correctos, el sistema guarda la información y agenda la cita, dando fin al proceso.

## Decisiones y validaciones

Se utilizaron gateways exclusivos para representar las decisiones del proceso, principalmente en las verificaciones realizadas por el sistema. Estas validaciones aseguran que la información seleccionada exista y esté disponible antes de continuar con el flujo. En caso de que alguna validación falle, el proceso permite realizar una nueva selección.

## Consideraciones de modelado

Durante el desarrollo del diagrama, se buscó representar el proceso de forma clara y ordenada, separando las responsabilidades del paciente y del sistema. También se incluyeron las validaciones necesarias para reflejar el funcionamiento real de un sistema de agendamiento de citas.