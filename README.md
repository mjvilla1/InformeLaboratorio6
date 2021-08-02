# InformeLaboratorio6

Integrantes: César Garnica - Jonathan Insuasti - Melany Villa

# 1. Objetivos 

      Objetivo General
     
    - Analizar y comprobar el teorema de máxima transferencia de potencia  mediante   la   resolución del ejercicio
    propuesto en la guía de práctica para identificar el uso correcto del teorema con su respectiva simulación 
    en un software de diseño electrónico.
    
    Objetivos Específicos
     - Verificar experimentalmente en forma cualitativa el método de máxima transferencia de potencia 
     - Conocer los fundamentos básicos del teorema de máxima transferencia de potencia
     - Comprobar las condiciones necesarias para que se cumpla el teorema de máxima transferencia de potencia
     - Comprobar   los   resultados   obtenidos   teóricamente   mediante   una   simulación  
     de un diseño electrónico.

    
# 2. Marco Teórico

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/maxima%20transferencia%20de%20potencia.PNG)

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Tabla%20%236.PNG)

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Tabla%20%236.1.PNG)

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Tabla%20%236.2.PNG)
# 3. Explicación  del procedimiento

1.-Para comenzar con la práctica correspondiente al laboratorio #6 es necesario tener conocimiento de cómo funciona el teorema de máxima transferencia de potencia 
como se muestra en el siguiente diagrama del circuito a experimentar 

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Circuito%20MTP.PNG)

2.-Una vez realizado un análisis del circuito se observa que consta de dos resistencias y una fuente de voltaje 
con su respectivo valor.


3.-Con el paso anterior se procede a la revisión del valor de cada uno de los componentes presentes en el circuito, 
al igual que los materiales utilizados para su respectiva realizacion. 

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Materiales%20MTP.PNG)

4.-Continuando con la práctica procedemos a armar el circuito conforme se muestra en la figura 

5.-Primero colocamos el protoboard en el cual se ubicarán las dos resistencias y la fuente de voltaje con sus respectivos valores del diagrama de la práctica, y procedemos a conectar un instrumento de medición (multímetro) el cual nos servirá para medir 
el voltaje y la corriente respectivamente activando sus funciones correspondientes.

6.-Procedemos a simular con la ayuda de nuestro simulador Tinkercad para todas las resistencias que estan a continuación 

220 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/220%20Ohm.PNG)

470 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/470%20Ohms.PNG)

680 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/680%20Ohms.PNG)


820 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/820%20Ohms.PNG)

1000 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/1000%20Ohms.PNG)

1500 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/1500%20Ohms.PNG)

1800 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Resistencia%20de%201800.PNG)

2200 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Resistencia%20de%202200.PNG)

3900 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Resistencia%20de%203900.PNG)

4700 Ω

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Resistencia%20de%204700.PNG)


7.-Para la práctica calculamos la potencia consumida por la resistencia RL, utilizando en esta ocasión el simulador DCACLab para asi medir con la ayuda de un vatímetro la potencia de cada una de las resistencia, el ejemplo de a continuación es con la resistencia de 1000 Ohms que es la que mas se aproxima a la resistencia interna de la fuente con la que podemos ver la máxima transferencia de potencia 

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Wattimetro.PNG)


#  4. Respuestas 

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Resistencias%201-5.PNG)

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/MTP%206-10%20Resistencias.PNG)


A continuacion se procede a poner en la tabla del resultado

![](https://github.com/mjvilla1/ImagenesLab6/blob/main/Tabla%20de%20resultados.PNG)

Respuestas a Interrogantes

¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta.

Si se cumple, cuando más cercano esta la resistencia particular a la resistencia de thevenin mayor es la transferencia 
de potencia con su valor

¿Cuál fue la potencia máxima en RL?

RL = 1000Ω = 46,51 mW.(watts)

¿Para qué valor de RL se obtiene la MTP?

RL = 1200 ohms

# 5. Video

https://youtu.be/oqu5joHA7x4

# 6. Conclusiones

- Como no existen medidores de potencia para circuitos de Corriente Directa es necesario medir el voltaje, 
corriente o ambos para calcular la potencia en un elemento resistivo.
- El teorema de la máxima transferencia de potencia, se deriva del teorema de Thevenin y el de Norton, 
con un poco de cálculo elemental: llegamos a la conclusión que la máxima potencia se da cuando la carga toma de 
resistencia de igual a la resistencia de Thevenin o Norton.
- La potencia en la resistencia variable, depende de los valores del circuito equivalente de Thevenin.
- 

# 7. Bibliografía 

Robbins, A. H. (2008). Análisis de Circuitos Teoria y Practica. Santa Fe-Mexico: Cengage Learning.
