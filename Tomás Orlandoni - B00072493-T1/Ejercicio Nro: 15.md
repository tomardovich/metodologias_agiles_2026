# Ejercicio Nro: 15
## Enunciado
Generar un plan de trabajo basado en SCRUM para resolver la siguiente tarea Objetivo: El objetivo de este ejercicio es que los alumnos universitarios practiquen la creación de historias de usuario para un sistema informático de presupuesto de construcción de galpones, utilizando la metodología ágil. Descripción del ejercicio:

Los alumnos deberán formar equipos de trabajo, de preferencia de 3 a 5 personas por equipo.
Cada equipo deberá seleccionar la temática de construcción de galpones para su sistema informático de presupuesto.
Los equipos deberán generar al menos tres historias de usuario para su sistema, basadas en la temática seleccionada. Cada historia de usuario debe incluir un título y una descripción que contenga los criterios de aceptación.
Las historias de usuario deben enfocarse en las funcionalidades y características clave del sistema informático, considerando aspectos como la creación de presupuestos detallados, seguimiento del presupuesto durante la construcción, inclusión de etapas, generación de informes, entre otros.
Los equipos deben asegurarse de que las historias de usuario sean claras, concisas y comprensibles, siguiendo las buenas prácticas de redacción de historias ágiles.
Al finalizar, cada equipo deberá presentar sus historias de usuario al resto de la clase, explicando el contexto de su sistema y los criterios de aceptación de cada historia.
Se fomenta el intercambio de ideas y la retroalimentación constructiva entre los equipos durante las presentaciones. Nota: Los equipos pueden utilizar ejemplos y situaciones hipotéticas para desarrollar las historias de usuario, considerando las necesidades y requisitos típicos de un sistema de presupuesto de construcción de galpones. Además, se recomienda utilizar herramientas como tarjetas o post-its para escribir y visualizar las historias de usuario durante el ejercicio.

## Resolución (En solitario)

Historia de Usuario 1
Título: Generación de presupuesto base por dimensiones.
Descripción: Como vendedor de la constructora, quiero ingresar las dimensiones básicas del galpón para obtener un costo estimado automático de los materiales base.
Criterios de Aceptación:
- El sistema debe permitir el ingreso de valores numéricos decimales para ancho, largo y alto.
- El sistema debe calcular automáticamente los metros cuadrados cubiertos.
- El sistema debe multiplicar los metros cuadrados por un valor de referencia preconfigurado y mostrar el costo total estimado en pantalla.
- Si algún campo se deja vacío, el sistema debe arrojar el mensaje de error: "Por favor, complete todas las dimensiones".

Historia de Usuario 2
Título: Inclusión y seguimiento de etapas de construcción.
Descripción: Como jefe de obra, quiero dividir el presupuesto total en etapas de construcción para realizar un seguimiento financiero del progreso de la obra.
Criterios de Aceptación:
- El usuario debe poder crear, editar o eliminar etapas personalizadas dentro de un presupuesto activo.
- El usuario debe poder asignar un porcentaje específico del presupuesto total a cada etapa.
- La sumatoria de los porcentajes asignados a todas las etapas no debe superar el 100% del presupuesto; de lo contrario, el sistema debe bloquear el guardado.
- El sistema debe permitir marcar una etapa como "Finalizada" y calcular el saldo restante del presupuesto.

Historia de Usuario 3
Título: Generación de informe en formato PDF.
Descripción: Como cliente potencial, quiero recibir el presupuesto detallado exportado en un archivo PDF para poder revisarlo sin conexión y compararlo con otras opciones.
Criterios de Aceptación:
- Debe existir un botón visible de "Exportar a PDF" en la vista final del presupuesto.
- El documento generado debe incluir obligatoriamente: fecha de emisión, validez de la oferta, dimensiones del galpón y el desglose de costos por etapas.
- El archivo debe llevar como membrete el logo de la constructora y los datos de contacto.
- El tiempo de generación y descarga del archivo no debe superar los 5 segundos.
