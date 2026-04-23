# grupo-01

## integrantes

- nombres apellidos github
- nombres apellidos github
- nombres apellidos github

## descripción del sintetizador realizado

3 párrafos explicando el proyecto

imagen del sintetizador en su contexto

audio o video del sintetizador en acción

## proceso y resultados del reloj y secuenciador

Logramos comprender y ensamblar el circuito de reloj y secuenciador que transforma pulsos eléctricos en un ciclo visual continuo, dividiendo el trabajo en dos etapas principales. Por la parte izquierda del diagrama armamos el generador de reloj utilizando un temporizador 555 configurado en modo astable, el cual emite un pulso constante de voltaje por su pin 3; comprobamos que el ritmo de estos pulsos lo podemos controlar y hacer más rápido o más lento simplemente ajustando el condensador C1 y la perilla del potenciómetro. Luego, conectamos esta señal a la parte derecha del circuito, donde usamos un chip contador de décadas CD4017 como secuenciador. Al hacer que el pulso del 555 entre al pin 14 del 4017, logramos sincronizar ambos componentes: cada latido le indica al 4017 que avance un paso, activando en orden las salidas Q0 a Q3 (pines 3, 2, 4 y 7).  Como resultado final, conseguimos que los 4 LEDs conectados a estas salidas se enciendan uno por uno en fila, creando un ciclo visual infinito!.

**Imagenes del proceso**
![Esquematico](./imagenes/)
![Resultados](./imagenes/)

## proceso y resultados de osciladores y amplificador

con chips 4093 y 386

incluir texto e imágenes sobre cableado, pruebas, resultados obtenidos.

## modificaciones realizadas a los circuitos originales

incluir texto, imágenes sobre modificaciones realizadas a los circuitos originales, incluyendo el proceso de diseño, pruebas y resultados obtenidos.

incluir modificaciones en posición, chips, parámetros, valores, etc.

## carcasas de cartón

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
