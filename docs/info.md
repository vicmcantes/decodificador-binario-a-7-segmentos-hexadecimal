<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

El funcionamiento es bastante sencillo, al introducir un numero en binario de 4 bits, la salida que le corresponde, es ese numero ahora en hexadecimal que se muestra en un display de 7 segmentos de anodo común. La entrada h, es un vector de 4 bits, y la salida S, es un vector de 7 bits. Para la salida S, el bit mas significativo corresponde al segmento a, y asi sucesivamente, hasta el bit menos significativo que corresponde al segmento g. Como es ánodo común, para indicar que esta encendido un segmento, se indica con un "0".
![display](https://github.com/vicmcantes/decodificador-binario-a-7-segmentos-hexadecimal/assets/165434004/2a957009-3e5c-467f-bb9b-59fced5c5660)
En la simulación podemos observar como cada valor que introducimos en la entrada, le corresponde una combinacion de salida que permite mostrar ese numero en el display de 7 segmentos de forma hexadecimal, es decir, hasta "F" que en decimal corresponde a 15.
![Simu](https://github.com/vicmcantes/decodificador-binario-a-7-segmentos-hexadecimal/assets/165434004/149fd13c-fc7e-4d7d-ad5e-c58ad6342ed7)

## How to test

Para comprobar el funcionamiento, es bastante simple, a la entrada se conecta una alimentación, de acuerdo al número que se desee mostrar en el display, para indicar un estado en alto o bajo, y de esta forma, formar ese número en binario. Para la salida es conveniente conectar un display de 7 segmentos (ánodo común) para corroborar su funcionamiento, de acuerdo a los pines que correspondan a cada segmento que se pueden observar en el codigo mas a detalle y que se menciono de manera concisa en el apartado anterior. 

## External hardware

Switches de entrada, para formar el numero de 4 bits binario, junto con su debida alimentacion, y un display de 7 segmentos (ánodo común), para visualizar su funcionamiento. 
