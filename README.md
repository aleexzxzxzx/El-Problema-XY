# El Problema XY


- Para ver la pagina [Click aquí](https://aleexzxzxzx.github.io/El-Problema-XY/)

## ¿Qué es?

El problema de XY es preguntar sobre su intento de solución en lugar de su problema real. Esto conduce a enormes cantidades de tiempo y energía desperdiciados, tanto por parte de las personas que piden ayuda como por parte de quienes brindan ayuda.

- El usuario quiere hacer X.
- El usuario no sabe cómo hacer X, pero cree que puede encontrar una solución si solo puede lograr hacer Y.
- El usuario tampoco sabe cómo hacer Y.
- El usuario pide ayuda con Y.
- Otros tratan de ayudar al usuario con Y, pero están confundidos porque Y parece un problema extraño que quiere resolver.
- Después de mucha interacción y pérdida de tiempo, finalmente queda claro que el usuario realmente quiere ayuda con X, y que Y ni siquiera era una solución adecuada para X.

El problema ocurre cuando las personas se atascan en lo que creen que es la solución y no pueden dar un paso atrás y explicar el problema en su totalidad

##  ¿Qué hacer al respecto?

- Siempre incluya información sobre una imagen más amplia junto con cualquier intento de solución.
- Si alguien pide más información, proporcione detalles.
- Si hay otras soluciones que ya ha descartado, comparta por qué las ha descartado. Esto proporciona más información sobre sus requisitos


Recuerde que si sus teorías de diagnóstico fueran precisas, no estaría pidiendo ayuda, ¿verdad?

##  Ejemplos

###  Ejemplo 1

n00b en realidad no quiere los últimos 3 chracters en un nombre de archivo, quiere las extensiones de archivo, así que ¿por qué pedir los últimos 3 caracteres?

    	<bob> ¿Cómo puedo hacer echo de los tres últimos caracteres de un nombre de archivo?
            <feline> If están en una variable: echo ${foo: -3}
            <feline> ¿Por qué 3 caracteres? ¿Qué es lo que realmente quieres?
            <feline> ¿Quieres la extensión?
            <bob> Sí.
            <feline> No hay garantía de que cada nombre de archivo tenga una extensión de tres letras.
            <feline> Entonces agarrar ciegamente tres caracteres no resuelve el problema.
            <feline> echo ${foo##*.}

### Ejemplo 2

Si Angela acababa de comenzar explicando que quiere evitar que otros detecten su SO, esta podría haber sido una discusión mucho más corta y productiva.

>Angela: 'nmap -O -A 127.0.0.1' devuelve algunas líneas que comienzan con 'OS:'. ¿Cómo cambiarlo?

>Obama: Busque en el código fuente nmap, descubra cómo calcula la parte de Linux y luego reescriba su pila TCP/IP para no operar de una manera que nmap pueda detectar.

>Angela: Sí, pero no sé sobre el sistema linux api en absoluto.

>Obama: Bueno, la huella digital de nmap se basa en la forma en que funciona la pila TCP/IP, no hay una forma real excepto reescribir las partes apropiadas de dicha pila.

>Angela: Realmente necesito evitar estos mensajes. ¿Puede iptables hacer este trabajo?

>Obama: Bueno, no use la detección del SO o el escaneo de versiones

>Angela: Quiero evitar que otros sepan el tipo de mi sistema operativo

♦ [Source](https://meta.stackexchange.com/questions/66377/what-is-the-xy-problem "What is the XY problem?") ♦ [Source 2](https://mywiki.wooledge.org/XyProblem "XyProblem")
