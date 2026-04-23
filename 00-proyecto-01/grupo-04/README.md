# el tincado-04

## integrantes
+ antonia loch
+ nicolás valdés
+ carla núñez

## descripción del sintetizador realizado

el tincado nace a partir de la práctica y aprendizaje que tuvimos a lo largo de las clases, donde como primer gran proyecto se nos propuso elaborar un sintetizador de cuatro pasos, el cual contiene los siguientes componentes: protoboard, chip NE555, chip CD4017, chip CD4093, chip LM386, cables dupont, resistencias (1k, 10k, 220Ω), capacitores (1µF, 10µF, 100µF), capacitores cerámicos (104 nF), potenciómetros (B100K), LED, parlante y batería 9v. con esto logramos seguir el esquemático que se nos otorgó para realizar nuestro propio módulo de sonido.

en nuestro caso, no hicimos variaciones dentro del esquemático que se nos entregó, ya que cuando logramos que funcionara el sintetizador fue gracias a la ayuda de nuestros compañeros Vania y Nicolás, los cuales, luego de escuchar que por fin el trabajo estaba emitiendo sonidos, nos recomendaron cambiar los capacitores que se encuentran dentro del circuito del chip 4093 por unos de 1µF. ya que nosotros los teníamos con capacitores de 10µF  y 100µF, lo cual no lograba hacer sonidos tan notorios como lo es ahora que solo tiene capacitores de 1µF, ya que este permite que circulen los electrones de manera más libre y así es como se logran los sonidos más agudos. a pesar de no tener cambios en los capacitores, sí tenemos cambios notorios en lo que es la parte del chip 555, el cual tuvo una intervención por nuestros compañeros y notamos un cambio en conexiones como lo es en el pin 4 y 8, lo cual desarrollaremos en su propia sección.


imagen del sintetizador en su contexto

audio o video del sintetizador en acción

## proceso y resultados del reloj y secuenciador

con chips 555 y 4017

incluir texto e imágenes sobre cableado, pruebas, resultados obtenidos.

## proceso y resultados de osciladores y amplificador

con chips 4093 y 386

incluir texto e imágenes sobre cableado, pruebas, resultados obtenidos.

## modificaciones realizadas a los circuitos originales

incluir texto, imágenes sobre modificaciones realizadas a los circuitos originales, incluyendo el proceso de diseño, pruebas y resultados obtenidos.

incluir modificaciones en posición, chips, parámetros, valores, etc.

## carcasas de cartón

para la carcasa de nuestro sintetizador, utilizamos cartón corrugado simple, pegamento (uhu) y cinta americana. decidimos diseñar un archivo en rhino para facilitar el trabajo y realizar el corte en láser, esto nos permitió enfocarnos mucho más en el circuito de nuestro proyecto. nos centramos en una estructura simple de forma rectangular, tomando como referente los sintetizadores del laboratorio de interacción digital.

la caja se diagramó por caras:
+ **cara superior:** contiene el sintetizador, el chip **4093** con los cuatro potenciómetros (**B2, B3, B4 y B5**), el clock generator, el chip **555** con el potenciómetro **B1**, un LED y el parlante para la salida de sonido.
+ **cara delantera:** contiene el estabilizador y el chip **LM386** con el potenciómetro **B6**.
+ **caras restantes:** consisten en cartón liso sin perforaciones.

![imagenes](./imagenes/modelo-tincado.jpg)


textos, imágenes

incluir origen de materiales, decisiones de posiciones de los componentes, decisiones estéticas, pruebas, resultados obtenidos.

## interconexión entre módulos

textos, imágenes, diagramas de interconexión

## resultados finales

texto

imagen

video / audio

## aprendizajes y errores

las mejores lecciones aprendidas y los errores más comunes y cómo los resolvieron

## conclusiones

sobre modularidad, materialidad, trabajo en equipo, trabajo electrónico, trabajo maquinal.
