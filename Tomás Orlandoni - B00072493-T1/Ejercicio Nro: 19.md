# Ejercicio Nro. 19: Creación de bots

## Consigna

Crear bots que representen diferentes roles relacionados con un equipo Scrum: Cliente, Scrum Master, Product Owner, Desarrollador y Product Owner encargado de la relación con los clientes.

## Resolución

### Parte 1: Creación de los Bots
Para crear cada bot, redacté un "System Prompt", es decir, la instrucción inicial que le da vida y personalidad al bot, basándome en los insumos y roles que se piden. Y se pueden usar estos textos como la configuración inicial de cada bot.

### 1. Bot Cliente (POE):

Prompt del bot: "Actúa como el Cliente del proyecto. Tus tareas principales son tres: formularás requerimientos al PO, realizarás pruebas de usuario, y calificarás releases. Siempre que interactúes, evaluá si el software cumple con el valor de negocio esperado y comunicá tus necesidades de forma clara al Product Owner."

### 2. Bot Scrum Master (POE):

Prompt del bot: "Asume el rol de Scrum Master del equipo. Tu objetivo es velar por el proceso Scrum y eliminar obstáculos. Diariamente coordinarás reuniones diarias recordando la hora, y llevarás un registro de impedimentos. Debes mantener un tono facilitador y ayudar al equipo a mantenerse enfocado."

### 3. Bot Product Owner (POE - Gestión):

Prompt del bot: "Eres el Product Owner enfocado en la gestión interna. Tus responsabilidades son administrar el Backlog y recordar fechas de Planning. Asegurate de que las historias de usuario estén siempre priorizadas y listas antes de cada ceremonia."

### 4. Bot Desarrollador (POE):

Prompt del bot: "Actúa como un miembro del Equipo de Desarrollo. Para gestionar tu trabajo, recordarás las tareas asignadas y permitirás el reporte de avances. Tu enfoque debe ser técnico, centrado en la implementación y en notificar al Scrum Master si surge algún bloqueante."

### 5. Bot PO (POE - Interacción):

Prompt del bot: "Eres el Product Owner enfocado en el frente externo. Tu función principal es interactuar con clientes para requisitos, y realizar encuestas de satisfacción. Debes ser empático, hacer las preguntas correctas para extraer valor y medir qué tan contento está el cliente con cada entrega."

## Parte 2: Preparación de la Presentación

### 1. Enumera todas las técnicas utilizadas en los prompts:
- Asignación de roles: Se definió un personaje específico para cada bot (ej. Scrum Master, Cliente).
- Historias de usuarios, tableros y clasificaciones de requerimientos: Utilizamos estas técnicas ágiles para estructurar la información.
- Prompting en cadena: En el ejercicio anterior, la salida de un bot se usó como entrada del siguiente para crear un flujo de trabajo continuo.
- Restricción de formato: Se le exigió al bot que devuelva listas específicas.

### 2. Indicar cuál fue la estrategia para contextualizar en los diferentes roles o etapas:
La estrategia para contextualizar en los diferentes roles o etapas consistió en estructurar cada prompt con tres bloques inamovibles:
- La Descripción de la actividad: Para setear la mente del bot en el momento exacto del Sprint.
- La Entrada/Salida: Para delimitar con qué datos cuenta y qué formato debe devolver.
- Las Instrucciones directas: el llamado a la acción.

### 3. Indicar qué tipo de resultados obtenidos son de poca calidad. Reflexionar cuál puede ser el motivo:
Al evaluar qué tipo de resultados obtenidos son de poca calidad y reflexionar cuál puede ser el motivo, a veces las "tareas técnicas" generadas por el bot Desarrollador pueden resultar demasiado genéricas (ej. "Programar el backend").

**El motivo:** Ocurre por la falta de contexto técnico en la "Entrada" del prompt. Si el modelo no recibe restricciones técnicas, asume la solución más superficial posible.

### 4. Indicar qué mejoras se pueden hacer a los prompts y a su proceso de creación:
Una gran actualización sería aplicar Few-Shot Prompting, o sea: darle ejemplos concretos. Por ejemplo, en lugar de solo pedirle "historias de usuario", brindarle un ejemplo de una historia de usuario perfecta para que la tome como plantilla.

### 5. Cómo sería un agente que utilice a todos los prompts para que el trabajo se realice de forma automática y en una acción:
Para entender cómo sería un agente que utilice a todos los prompts para que el trabajo se realice de forma automática y en una acción, debemos imaginar un programa "Orquestador". Este agente funcionaría con un único botón de "Inicio". El usuario solo cargaría el requerimiento inicial. El Orquestador llamaría automáticamente al Bot Cliente para refinar la idea, pasaría esos datos al Bot PO para armar el Backlog, activaría al Bot Scrum Master para planificar, enviaría las tareas al Bot Desarrollador para generar el incremento, y finalmente recopilaría todo en un reporte de entrega. Todo el ciclo de vida del software simulado ocurriría en cuestión de segundos, pasándose la información por debajo de la mesa sin que el humano tenga que copiar y pegar nada entre pasos.
