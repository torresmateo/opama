# opama
Análisis de datos de transporte del área metropolitana de Asunción

# Resultados preliminares

Con estadísticas simples se ven algunos casos que resultan poco razonables si uno piensa en un pasajero convencional. Por ejemplo, usar un servicio de bus 662 veces en el mismo día (particularmente un Domingo).

![Histograma de número de eventos de la tarjeta con más eventos en un día](img/hist-dia-max-eventos.png)

Otro ejemplo es el de una tarjeta que gastó más de Gs 50.000.000 entre Julio 2022 y Marzo 2023. Podemos ver el día con más eventos de esta tarjeta, donde usó un mismo bus 218 veces. La única explicación razonable es que esta tarjeta fuese validada por el chofer de forma constante.

![mapa e histograma de eventos de la tarjeta con más gastos en el período de análisis.](img/mapa-histograma.png)

Esta misma tarjeta, consistentemente gasta múltiples veces el valor del salario mínimo en pasajes.

![desglose de gastos mensuales de la tarjeta con más gastos en el período de análisis](img/gastos-por-mes.png)