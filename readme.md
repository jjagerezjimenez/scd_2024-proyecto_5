# Proyecto 4 - Modulaciones digitales

Sistemas de Comunicaciones Digitales I - 2024

## Objetivos

- Investiga sobre la representación de Fourier de formas de onda de energía finita.
- Determina la transformada de Fourier de las formas de onda siguientes *pulso rectangular*, *pulso seno cardinal*, *pulso coseno elevado* (para distintos valores del parámetro) y *pulso raiz cuadrada de coseno elevado* (para los mismos valores del parámetro). Determina el ancho de banda que contiene al menos el 90% de la energía de la forma de onda en cada caso.
- Determina el ancho de banda necesario para una transmisión con una tasa de transferencia de un bit por segundo utilizando modulación en amplitud de pulso binaria (2-PAM), para pulsos de forma rectangular, seno cardinal y raiz cuadrada de coseno elevado.
- Investiga la condición de "cero interferencia entre símbolos".
- Analiza la interferencia entre símbolos para señales 2-PAM con forma de pulso raiz cuadrada de coseno elevado antes y después de pasar por un filtro de respuesta al impulso raiz cuadrada de coseno elevado con los mismos parámetros de la forma de pulso utilizada (filtro adaptado).
- Analiza a inteferencia entre símbolos para una señal 2-PAM con forma de pulso rectangular y tasa de transferencia de un bit por segundo, luego de que pasa por un canal con respuesta en frecuencia pasa-bajo de un polo cuya frecuencia de corte es medio Hertz.
- Analiza a inteferencia entre símbolos para una señal 2-PAM con forma de pulso raiz cuadrad de coseno elevado y tasa de transferencia de un bit por segundo, luego de que pasa por un canal con respuesta en frecuencia pasa-bajo de un polo cuya frecuencia de corte es medio Hertz y por un filtro adaptado.

Utiliza modelos numéricos para plantear las situaciones descritas y analizar los resultados.

## Entregables

Una monografía con la siguiente estructura:

- *Título*
- *Autor*
- *Resumen*. Explica de qué trata la monografía y los principales resultados de la investigación. De leer el resumen, un lector debe poder conocer qué se investigó y las conclusiones generales a las que se arribó.
- *Introducción*. Esta sección pone el tema en contexto y define el alcance de la monografía.
- *Desarrollo* (varias secciones). Cada sección explora un aspecto del tema tratado.
- *Conclusiones*. Aquí el autor sintetiza con sus propias palabras los aspectos más importantes que surgieron de su investigación. Todo lo expuesto debe ser respaldado por el desarrollo (no se puede concluir sobre algo que no se desarrolló).
- *Referencias*. Referencias bibliográficas utilizadas

El código fuente empleado durante la investigación. Cuando presentes tus resultados en la monografía harás referencia al código fuente incluido. Debe ser posible replicar tus resultados con dicho código.

## Evaluación

La evaluación será en base a una monografía presentando los resultados y el código fuente desarrollado durante la investigación. La calificación será el promedio de las calificaciones de ambos item.

### Monografía

La monografía será evaluada según los siguientes criterios:

- Cada sección cumple con la descripción dada en la sección Entregables.
- Cada concepto expuesto *Introducción* y *Desarrollo* es o bien paráfrasis de resultados hayados en la investigación bibliográfica y el autor **cita correctamente las fuentes** o bien son desarrollos originales del autor. En el caso de desarrollos originales debe indicarse la meotodología empleada y presentarse los resultados obtenidos. Referenciar en el trabajo el código fuente empleado para obtener los resultados, que debe ser incluido por separado.
- Las conclusiones *se apoyan en el desarrollo*, es decir, solo puede concluirse sobre lo expuesto.
- Las conclusiones son *objetivas* (relativas a los resultados y hechos expuestos)
- Todos los trabajos citados están referenciados en la sección *Referencias* según las normas APA.
- Todos los trabajos referenciados han sido utilizados en la investigación (y por lo tanto son citados en el texto)

Cada criterio será valorado en la siguiente escala

- 0 (Nunca cumple con el criterio)
- 2,5 (La mayor parte no cumple con el criterio)
- 5 (Hay tantas instancias de cumple como no cumple)
- 7,5 (La mayor parte cumple con el criterio)
- 10 (Siempre cumple con el criterio)

La valoración de la monografía será la **media geométrica** de las valoraciones individuales. Consecuencia: Si algún criterio falla siempre la calificación será cero.

### Código fuente

El código fuente incluido debe permitir replicar los resultados presentados, y la monografía debe incluir suficiente información para poder utilizar dicho código fuente. El puntaje será la suma de los siguientes criterios:

- El código fuente permite replicar los resultados presentados. 5 puntos
- La monografía incluye suficiente información para ejecutar correctamente el código fuente. 2,5 puntos
- El código fuente se ejecuta sin producir errores (sobre las versiones de Python/gnuradio/etc. indicadas). 2,5 puntos

