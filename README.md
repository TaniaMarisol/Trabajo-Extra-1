# Trabajo-Extra-1

Tema: Construcción y simulación de una fuente de alimenta básica con transformador.

1. Objetivos

1.1. Objetivo General 

Realizar una investigación pertinente sobre varios conceptos básicos que van a ser de gran utilidad al momento de cronstruir una fuente de alimentación básica con transformador, mediante la aplicación de conocimientos previamente revisados en clase, lo cual permite desarrollar la destresa de diseño de un circuito. 

1.2. Objetivos Específicos

Identificar los conceptos generales que se relacionen con la fuente de alimentación básica con transformador .

Diseñar el modelo de circuito en cualquier simulador, para verificar  los componentes que sean necesarios para su contrucción. 

Armar la fuente de alimentación y verificar su funcionalidad. 

2. Marco teórico 

![Untitled Diagram-Page-2 drawio](https://user-images.githubusercontent.com/94153604/155932296-70c500e7-039b-4157-94aa-3147bb267929.png)

3. Requisitos Previos 

![image](https://user-images.githubusercontent.com/94153604/155932430-4c9c00eb-69d5-48e4-a79f-a32299ba697b.png)

![image](https://user-images.githubusercontent.com/94153604/155932503-b9f7a365-1d2d-474d-bdaf-2d81384f98d8.png)

![image](https://user-images.githubusercontent.com/94153604/156412332-f1adc4a6-046b-4db6-bd87-d052db550a83.png)

![image](https://user-images.githubusercontent.com/94153604/156412476-74b2e44d-1d60-43db-b857-fbefd719780f.png)

![image](https://user-images.githubusercontent.com/94153604/156412579-91bb3cfa-bc6d-457d-a64a-769d5a4878c9.png)

![image](https://user-images.githubusercontent.com/94153604/156412716-45406ee0-f4db-44cc-b51d-022d84fe846e.png)

![image](https://user-images.githubusercontent.com/94153604/156506961-dab5f0d8-4178-4ea0-88f1-d69a04f7d1e9.png)

4. Materiales y equipios resqueridos 

![image](https://user-images.githubusercontent.com/94153604/156411226-b89a8e0f-36ce-4cd1-b2ff-724874b24313.png)

5. Procedimiento 

![image](https://user-images.githubusercontent.com/94153604/156503604-07965193-e059-4609-b88b-75e06d6fa23a.png)

El transformador que se utilizo para todo el circuito de de 12 a 24 voltios, pero en este caso se va a trabajar con 12 V y para ello se utilizara el cable de color rojo y azul, puesto que si se trabaja con el negro en vez del azul se estara utilizando los 24 V. 

![image](https://user-images.githubusercontent.com/94153604/156503784-dfa73c1e-d7f5-41dc-a6fd-9f9cffd8760a.png)

Se conceta el transformador en la entrada negativa y positiva y de ahì se va a proceder a armar el ciruito y para ello encontramos el primer elemento que es el rectificador en el cual tiene sus enntradas y salidas negativas y positivas. 

![image](https://user-images.githubusercontent.com/94153604/156503979-868e52fa-5261-4b92-82c4-2749d373dadb.png)

Para cada salida positiva y negativa se trabajo con las doshileras de la placa para trabajar de mejor manera.

![image](https://user-images.githubusercontent.com/94153604/156504085-0f503dfd-3293-45ed-b28d-81fc8722264c.png)

El segundo elemento es el capacitor de 2200 μF  que del mismo modo se verifica el positivo y negativo para poderlo conectar 

![image](https://user-images.githubusercontent.com/94153604/156504615-90a5e639-96b5-4f1d-9adb-03a2aedaefb4.png)

Despues se conecta la resistencia de 270 Ω y el let . 

![image](https://user-images.githubusercontent.com/94153604/156504919-fad8ecae-efb9-472e-b0a6-71ff8ed12ca8.png)

Siguiendo el circuito armado en el programa se encuentra el ML317T el cual tiene tres entrasdas la primera es el int, la segunda el out y la tercera adj , para lo cual en el circuita la primara va a ser alimantada al positivo, en la segunda se encuentra conectada la resistencia y en la última entrada se encuentra el potenciometro y de igual manera la resistencia de 270 Ω. Uno de los diodos zener esta de manera paralela conectado con la salida uno y dos. 

![image](https://user-images.githubusercontent.com/94153604/156505708-c92d0f26-a4a8-49b2-86b9-e8cc0364b6e6.png)

El potenciometro tiene tres salidas la primera esta conectada con el ML317T la ultima salida adj, y las otras salidas del potenciometro se alimentan con el positivo . 

![image](https://user-images.githubusercontent.com/94153604/156506015-6d91ce68-5668-49f8-ab1d-09c300ecbd00.png)

Se alimenta la siguiente parte del proto para seguir armando el circuito de ahí se va a conectar lo que es el diodo y el capacitor de 10 µF , de igual manera se los relaciona entre si con positivo y negativo, se los alimenta y por ultimo se puede utilizar otra resitencia y un let para observar como varia el voltaje a travez de potenciometro o solo con el uso de un multimentro obtener la medida del voltaje. 

![image](https://user-images.githubusercontent.com/94153604/156506703-6210491a-193d-464b-a87c-467849a2895a.png)

Este seria el circuito con el let al final 

![image](https://user-images.githubusercontent.com/94153604/156506812-d7a14633-eb1d-4800-992b-4fd1bef78693.png)

Utilizando el multimentro.

6. Video 

https://youtu.be/KqVPnk5UU5U

7. Conclusiones 

La fuente de alimentanci es de gran utilidad puesto que transforma de corriente alterna a correinte continua , además de regular o cambiar la tensión de salida a valores determinados , por ello si se conecta a una fuente de alimentación de 120 V  en corriente alterna la transforma en el caso del circuito realizado seria que lo transforma a corriente continua con una salida de 12 V. Al utilizar el tranformador es para disminu la tensión antes de llegar al circuito. 

Para realizar la fuente de alimentación se utilizó elementos ya conocidos como son los capacitores, las resitencias y el potenciomentro, sim embargo de igual manera se encuentra presente en el circuito lo que son los diodos zener que se lo utiliza como estabilizador, también hay lo que es un rectificador o también conocido como un puente de diodo, y por último el LM317T es un regulador positivo. 

La fuente de alimentación armada puede variar el voltaje de salida por medio del potenciometro y para que sea más obserbable  se muestra de dos maneras uno con un let el cual si disminuye el volteje de salida el let tiene que disminuir su luminosisdad y si aumenta la luminosidad de igual manera y el otro modo de comprobarlo es por medio del uso del multimentro . 

8. Bibliografía

Chiikiy. (2 de Diciembre de 2013). Area Tecnologia. Obtenido de https://www.areatecnologia.com/electronica/fuente-alimentacion.html

