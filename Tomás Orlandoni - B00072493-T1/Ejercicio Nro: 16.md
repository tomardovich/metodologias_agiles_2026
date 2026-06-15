# Ejercicio Nro: 16

## Enunciado
Objetivo

Utilizar el método Delphi para llegar a un consenso sobre la tecnología y la arquitectura más adecuadas para el desarrollo de una billetera virtual segura, escalable y confiable.

Descripción

El método Delphi es una técnica de consulta estructurada que se utiliza para obtener opiniones expertas sobre un tema complejo. En este caso, el método Delphi se utilizará para recopilar información y opiniones de expertos en blockchain, seguridad, desarrollo de software y arquitectura de sistemas sobre la mejor tecnología y arquitectura para una billetera virtual.

1. Definición del problema
Describir claramente los objetivos y requisitos de la billetera virtual, tal como se presentó en el enunciado anterior.
Identificar los factores clave que se deben considerar al seleccionar la tecnología y la arquitectura, como la seguridad, la escalabilidad, la confiabilidad, la facilidad de uso y el costo.
2. Selección del panel de expertos
Identificar y reclutar a un grupo de expertos con experiencia en las áreas relevantes, como blockchain, seguridad, desarrollo de software y arquitectura de sistemas.
El panel de expertos debe estar compuesto por individuos con diferentes perspectivas y experiencias para garantizar la diversidad de opiniones.
Es importante que los expertos sean independientes y no tengan conflictos de intereses.
3. Elaboración del cuestionario
Diseñar un cuestionario que presente a los expertos una lista de opciones de tecnología y arquitectura para la billetera virtual.
El cuestionario debe incluir preguntas que permitan a los expertos evaluar cada opción en función de los factores clave identificados en el paso 1.
Las preguntas pueden ser de tipo Likert, abiertas o una combinación de ambas.
4. Aplicación del método Delphi
Distribuir el cuestionario a los expertos de forma anónima.
Recopilar las respuestas de los expertos y analizarlas estadísticamente.
Sintetizar los resultados y presentarlos al panel de expertos.
Brindar a los expertos la oportunidad de revisar y comentar los resultados.
Realizar una segunda ronda de cuestionarios, incorporando los comentarios de la primera ronda.
Analizar nuevamente las respuestas y presentar los resultados finales al panel de expertos.
5. Selección de la tecnología y la arquitectura
Con base en los resultados del método Delphi, seleccionar la tecnología y la arquitectura que mejor se adapten a los objetivos y requisitos de la billetera virtual.
Justificar la selección de la tecnología y la arquitectura elegidas, considerando los aportes del panel de expertos y los resultados del análisis estadístico.
6. Documentación y comunicación
Documentar cuidadosamente el proceso de toma de decisiones, incluyendo los criterios utilizados, las opciones consideradas y la justificación de la selección final.
Comunicar la decisión tomada a las partes interesadas, incluyendo a los desarrolladores, inversores y usuarios potenciales.

## Resolución

1. Definición del problema
a) Objetivos y requisitos de la billetera virtual:

Desarrollar una billetera virtual multiplataforma que permita a los usuarios almacenar, enviar, recibir e intercambiar fondos de manera segura, rápida y transparente, soportando un ecosistema financiero híbrido.
Con: Disponibilidad multiplataforma, procesamiento de transacciones con baja latencia, un sistema robusto de recuperación de cuenta y resguardo de claves e integración mediante APIs con bancos tradicionales y pasarelas de pago.

b) Factores clave para la selección de tecnología y arquitectura:
- Seguridad: Requiere encriptación de grado militar, protección de datos personales, autenticación multifactor, prevención de fraudes y auditorías contra vulnerabilidades.
- Escalabilidad: La arquitectura debe ser elástica, capaz de soportar aumentos bruscos de usuarios concurrentes y un alto volumen de transacciones por segundo sin que el sistema se caiga o se vuelva lento.
- Confiabilidad: El sistema debe garantizar alta disponibilidad, redundancia de datos y tolerancia a fallos para que los usuarios siempre tengan acceso a sus fondos.
- Facilidad de uso: El diseño debe abstraer la complejidad técnica para ofrecer una interfaz limpia, amigable y fácil de usar para cualquier persona, sin importar su nivel tecnológico.
- Costo: Balancear el presupuesto. Se deben contemplar los costos de infraestructura, el tiempo/costo de desarrollo de la tecnología elegida y los costos operativos.

2. Selección del plantel de expertos
Para garantizar un análisis integral y sin sesgos de la tecnología y arquitectura de la billetera virtual, se podrían reclutar al siguiente panel de cuatro expertos independientes:

Experto A - Arquitecto de Sistemas Cloud:
- Experiencia: 15 años diseñando infraestructuras para empresas fintech tradicionales y bancos digitales.
- Perspectiva: Su enfoque principal es la escalabilidad, la alta disponibilidad y la integración de microservicios.

Experto B - Especialista en Ciberseguridad Financiera:
- Experiencia: Consultora independiente especializada en auditoría de plataformas de pago y prevención de fraudes.
- Perspectiva: Su prioridad absoluta es la seguridad y la confiabilidad. Evalúa cada tecnología en función de sus vulnerabilidades, protección de datos del usuario final y encriptación.

Experto C - Desarrollador Core Blockchain:
- Experiencia: Investigador académico y desarrollador de contratos inteligentes en redes públicas y privadas.
- Perspectiva: Aporta la visión de vanguardia técnica. Su enfoque está en la descentralización, la inmutabilidad de las transacciones y cómo reducir el costo de las tarifas de red.

Experto D - Product Manager de UX:
- Experiencia: Ha liderado el lanzamiento de múltiples aplicaciones móviles de finanzas personales dirigidas al público general.
- Perspectiva: Su objetivo es la facilidad de uso. Defiende que cualquier tecnología subyacente debe ser completamente invisible para el usuario, logrando una adopción masiva sin fricciones.

3. Elaboración del cuestionario
- En la escala del 1 al 5: ¿Qué tan adecuado considera implementar una Arquitectura de Microservicios frente a una Arquitectura Monolítica tradicional?
- En la escala del 1 al 5: ¿Qué nivel de viabilidad le asigna a utilizar una Blockchain Pública pura para el núcleo transaccional?
- En la escala del 1 al 5: ¿Qué nivel de viabilidad le asigna a utilizar una Blockchain Híbrida o Privada/Permisionada?
- En la escala del 1 al 5: ¿Qué tan seguro y eficiente considera alojar la infraestructura completa en una Nube Pública en lugar de utilizar Servidores On-Premise?
- Basado en su experiencia, ¿cuál considera que es el mayor cuello de botella o riesgo crítico de seguridad al integrar el mundo del dinero fiduciario con los activos digitales en esta billetera, y cómo lo mitigaría desde el diseño inicial?

4. Aplicación del Método Delphi (Simulación)
- Fase 1: Primera Ronda y Análisis Inicial
Se distribuyó el cuestionario a los 4 expertos de forma anónima. Tras recopilar las respuestas, el análisis estadístico mostró lo siguiente:

Pregunta 1 - Los 4 expertos coincidieron en utilizar una Arquitectura de Microservicios. Argumentan que es la única forma de escalar partes específicas de la app. sin sobrecargar todo el sistema.

Pregunta 2 - Hubo alta divergencia.
El Experto C votó por una red Pública por su máxima transparencia.
Los Expertos A y D votaron por una red Híbrida/Capa 2 para evitar las altas comisiones que pagarían los usuarios y asegurar rapidez.
El Experto B votó por una red estrictamente Privada para tener control total sobre quién valida las transacciones.

Pregunta 3 - Hubo divergencia moderada.
Los expertos A, C y D optaron por la Nube Pública por su elasticidad. 
El Experto B prefirió servidores propios argumentando riesgos de fugas de datos en la nube.

- Fase 2: Segunda Ronda y Búsqueda de Consenso
Redactamos un informe resumiendo los resultados y se los devolvimos a los expertos, dándoles la oportunidad de leer las justificaciones de los demás de forma anónima y reconsiderar su voto.

Comentario del Experto C: "Al leer las preocupaciones del experto en UX sobre los costos para el usuario final, reconsidero mi postura. Propongo una Blockchain Híbrida o Permisionada que nos da las ventajas criptográficas pero con transacciones casi gratuitas y rápidas."
Comentario del Experto B: "Acepto la Blockchain Híbrida propuesta si los nodos validadores son instituciones de confianza. Respecto a la infraestructura, cederé a usar la Nube Pública siempre y cuando implementemos HSM dedicados en la nube para custodiar las claves criptográficas, mitigando así el riesgo de hackeos."

Fase 3: Resultados Finales
Tras la segunda ronda, las respuestas se alinearon y se alcanzó el consenso necesario:

- Arquitectura: Microservicios (100% de acuerdo).
- Tecnología Core: Blockchain Híbrida/Permisionada (100% de acuerdo tras las concesiones).
- Infraestructura: Cloud Pública con módulos de seguridad de hardware o HSM (100% de acuerdo).

5. Selección de la tecnología y la arquitectura

En base a los resultados unánimes alcanzados tras la segunda ronda del método Delphi, se ha determinado que la solución tecnológica y arquitectónica más adecuada para los objetivos de la billetera virtual estará compuesta por: 
- Arquitectura de Microservicios: Permitiendo escalar recursos de forma independiente y asegurar que, si un módulo falla, la billetera en su totalidad no se caiga.
- Blockchain Híbrida o Permisionada: Satisfaciendo al experto en Blockchain garantizando la inmutabilidad de los registros, mientras cumple el requisito del experto en UX al permitir transacciones casi instantáneas y sin costo directo para el usuario,
- Nube Pública complementada con Módulos de Seguridad de Hardware dedicados: De este modo, las claves criptográficas y los fondos de los usuarios permanecen aislados en hardware físico inviolable, asegurando un entorno de "confianza cero" dentro de la nube.
