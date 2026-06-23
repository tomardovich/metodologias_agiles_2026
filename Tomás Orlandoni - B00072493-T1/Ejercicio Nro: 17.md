# Ejercicio 17

# Consigna

Desarrollar una aplicación web que permita a los usuarios gestionar sus finanzas personales de manera eficiente y segura. La aplicación debe cumplir con los siguientes requisitos funcionales:

1. Gestión de cuentas bancarias

Permitir la creación y edición de cuentas bancarias.

Visualizar el saldo actual y el historial de movimientos de cada cuenta.

Realizar transferencias entre cuentas propias.

Descargar el historial de movimientos en formato CSV o PDF.

2. Gestión de ingresos y gastos

Permitir la creación y edición de ingresos y gastos.

Categorizar los ingresos y gastos por tipo, por ejemplo: salario, alquiler, alimentación, etc.

Visualizar gráficos y reportes sobre los ingresos y gastos por categoría y período de tiempo.

Establecer presupuestos para diferentes categorías de gastos.

3. Gestión de deudas

Permitir la creación y edición de deudas.

Indicar el monto total de la deuda, la tasa de interés, el plazo de pago y el monto de las cuotas.

Visualizar un calendario de pagos y realizar simulaciones de diferentes escenarios de pago.

Generar informes sobre el progreso en el pago de las deudas.

Resolver
Estimación del tamaño del proyecto

Utilizando el método COSMIC, se estima que el tamaño funcional total del proyecto es de X Puntos de Función COSMIC (PFC).

Cálculo del costo por punto de función

El costo por punto de función (CPFC) se estima en Y USD.

Cantidad de puntos de función que se pueden hacer en un mes

Se estima que un equipo de desarrollo de software de Z personas puede desarrollar W Puntos de Función COSMIC (PFC) por mes.

Duración del proyecto

La duración del proyecto se estima en A meses.

Costo del proyecto

El costo total del proyecto se estima en B USD.

Instrucciones para el alumno
Identificar las interacciones funcionales: analice los requisitos funcionales descritos anteriormente e identifique todas las interacciones entre los usuarios y la aplicación.
Clasificar las interacciones funcionales: clasifique cada interacción funcional en una de las tres categorías de tamaño COSMIC: pequeña (S), mediana (M) o grande (L).
Calcular el tamaño funcional: asigne un valor de Puntos de Función COSMIC (PFC) a cada interacción funcional en función de su clasificación de tamaño y sume los valores de PFC de todas las interacciones para obtener el tamaño funcional total del proyecto en PFC.
Obtener el costo por punto de función: investigue el costo promedio de desarrollo de software en su región y considere la complejidad del proyecto para estimar el costo por punto de función (CPFC).
Determinar la cantidad de PFC por mes: estime la cantidad de Puntos de Función COSMIC (PFC) que un equipo de desarrollo de software de tamaño Z puede desarrollar por mes (W PFC/mes) en función de su experiencia y eficiencia.
Calcular la duración del proyecto: divida el tamaño funcional total del proyecto (X PFC) por la cantidad de PFC que se pueden desarrollar por mes (W PFC/mes) para obtener la duración estimada del proyecto en meses (A meses).
Estimar el costo total: multiplique el tamaño funcional total del proyecto (X PFC) por el costo por punto de función (Y USD/PFC) para obtener el costo total estimado del proyecto (B USD).

# Resolución

Cómo estamos desarrollando una Aplicación Web de Gestión de Finanzas Personales (PFM). Esta se trata de una plataforma accesible directamente desde el navegador, orientada a la organización económica individual. Por un lado, funciona como un sistema transaccional que permite registrar y administrar de forma constante operaciones diarias como actualización de saldos, transferencias, gastos y nuevas deudas. Y por otro lado, actúa como un sistema analítico que procesa toda esta información para devolver valor agregado al usuario mediante reportes visuales, gráficos categorizados y simulaciones matemáticas para proyectar escenarios de pago.

## 1. Identificación, Clasificación y Medición de interacciones funcionales

En el módulo de Gestión de cuentas bancarias, identificamos cuatro interacciones principales. La creación y edición de cuentas bancarias, así como la capacidad de visualizar el saldo actual y el historial de movimientos, son interacciones de complejidad Mediana (M), aportando 5 PFC cada una. Del mismo modo, la función para realizar transferencias entre cuentas propias también se clasifica como Mediana (M) con 5 PFC. Por otro lado, la tarea de descargar el historial de movimientos en formatos CSV o PDF es más sencilla, por lo que se categoriza como Pequeña (S), sumando 3 PFC.

Pasando al módulo de Gestión de ingresos y gastos, la creación y edición de estos registros se clasifica como Mediana (M) con un valor de 5 PFC. La acción de categorizar los ingresos y gastos por tipo es una interacción más directa y simple, evaluada como Pequeña (S) con 3 PFC. En contraste, la visualización de gráficos y reportes interactivos requiere un mayor procesamiento y cruce de datos, por lo que se considera una interacción Grande (L) y aporta 7 PFC. Finalmente, la función para establecer presupuestos según diferentes categorías se clasifica como Mediana (M), sumando otros 5 PFC.

En el último módulo, enfocado en la Gestión de deudas, la creación y edición de deudas (que implica registrar variables como monto, tasa, plazo y cuota) se evalúa como Mediana (M) con 5 PFC. La funcionalidad que permite visualizar un calendario de pagos y realizar simulaciones de escenarios es una de las más complejas del sistema debido al motor de cálculo involucrado, por lo que se clasifica como Grande (L) con 7 PFC. Por último, la generación de informes sobre el progreso de pago se considera Mediana (M), sumando 5 PFC.

## 2. Cálculo del Tamaño Funcional (X)

Al sumar los valores de todas las interacciones descritas en estos tres módulos, se obtiene el tamaño funcional total del proyecto (X), que equivale a 55 Puntos de Función COSMIC (PFC).

## 3. Obtener el Costo por Punto de Función (Y)
Para estimar el costo, tomamos como referencia los valores promedio de desarrollo de software en la región.

Esfuerzo promedio: Desarrollar 1 PFC toma aproximadamente 10 horas de trabajo.

Tarifa horaria: Una tarifa promedio combinada para un equipo de desarrollo ronda los 20 USD por hora.

Cálculo: 10 horas * 20 USD/hora = 200 USD por PFC.

Y (Costo por Punto de Función - CPFC) = 200 USD.

## 4. Determinar la Cantidad de PFC por mes (W y Z)
Definimos un equipo de desarrollo estándar y calculamos su velocidad de entrega.

Z (Tamaño del equipo): 3 personas (ej. 2 Desarrolladores, 1 Analista/QA).

Productividad: Si un desarrollador trabaja un promedio de 160 horas al mes, y cada PFC requiere 10 horas, la capacidad teórica es de 16 PFC por persona. Ajustando por reuniones, pruebas y gestión, estimamos una productividad neta de 12 PFC por persona al mes.

Cálculo: 3 personas * 12 PFC/mes = 36 PFC/mes.

W (PFC desarrollados por mes) = 36 PFC/mes.

## 5. Calcular la Duración del Proyecto (A)
La duración se obtiene dividiendo el tamaño total del proyecto por la capacidad de desarrollo mensual del equipo.

Cálculo: 55 PFC (Total) / 36 PFC/mes (Velocidad) = 1.52 meses.

A (Duración del proyecto) = 1.5 meses (Aproximadamente 6 semanas).

## 6. Estimar el Costo Total (B)
El costo total se calcula multiplicando el tamaño funcional total por el costo unitario de cada punto de función.

Cálculo: 55 PFC (Total) * 200 USD (CPFC) = 11,000 USD.

B (Costo total del proyecto) = 11,000 USD.

## Resumen Final de Variables Solicitadas
- X: 55 PFC
- Y: 200 USD
- Z: 3 personas
- W: 36 PFC/mes
- A: 1.5 meses
- B: 11,000 USD
