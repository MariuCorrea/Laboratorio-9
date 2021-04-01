# Laboratorio-9
Mariú Correa      David López
## INFORME LABORATORIO 9
FDC 4877
- Mariú Correa
- David López
----------------

### OBJETIVOS
#### Objetivo General
-   Identificar el principal funcionamiento de un Amplicador Operacional.
-   Realizar análisis experimentales del comportamiento de un amplificador operacional.
#### Objetivos específicos 
- Conocer las aplicaciones básicas que se desarrolan mediante un amplificador operacional.
- Realizar circuitos mediante el uso de amplificadores operacionales; facilitando así la observación del funcionamiento mediante un osciloscopio,
- Establecer la relación que existe entre las señales que se generan en la entrada y salidad de cada circuito a simular.
- Investigar los usos generales de un Amplificador Operacional y sus parámetros técnicos a considerarse.

### MARCO TEÓRICO 

![Amplificador Operacional](https://user-images.githubusercontent.com/76136485/113254969-dfa2d780-928c-11eb-9761-319550ddd93f.jpg)

### DIAGRAMAS
- Circuito numero 1 con su respectiva emulación e imágen de onda.

![1 1](https://user-images.githubusercontent.com/76136049/113253520-f9dbb600-928a-11eb-8be4-170598c792ba.PNG)
![1](https://user-images.githubusercontent.com/76136049/113253521-f9dbb600-928a-11eb-80bf-a807f3315989.PNG)
- Circuito numero 2 con su respectiva emulación e imágen de onda

![2 1](https://user-images.githubusercontent.com/76136049/113253522-fa744c80-928a-11eb-9189-ae27c66a86e4)
![2](https://user-images.githubusercontent.com/76136049/113255437-75d6fd80-928d-11eb-9eaf-7e0f4e37f683.jpg)
.PNG)
- Circuito numero 3 con su respectiva emulación e imágen de onda

![3 1](https://user-images.githubusercontent.com/76136049/113253523-fa744c80-928a-11eb-9a78-d41633eef441.PNG)
![3](https://user-images.githubusercontent.com/76136049/113253524-fa744c80-928a-11eb-8d36-0dfba25845ad.PNG)


### LISTA DE COMPONENTES

![Lista de componentes](https://user-images.githubusercontent.com/76136485/113254413-26440200-928c-11eb-9108-824cc8b38342.png)

### EXPLICACIÓN

[Link Video] https://www.youtube.com/watch?v=770NYZYMU04

### Análisis de resultados
Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos en el trabajo preparatorio. Comente dicha comparación.

En el primer circuito podemos observar en las gráficas que el voltaje de salida es mucho mayor que el voltaje de entrada, la cual consiste en V3 + VR1, comparando con los demás circuitos se puede observar que si R en paralelo al amplificador es mayor a la resistencia del voltaje de entrada, esto es lo que causa que el voltaje de salida sea mayor.

En el segundo circuito 2, habiendo observado los sucesos del circuito 1, podemos concluir que el voltaje de salida del amplificador va a depender de la resistencia que está en paralelo a éste. Este es un caso especial en la cual esta resistencia es un capacitor, en este caso especial envez de aumentar el voltaje lo que sucede es que el voltaje de salida se convierte en una corriente directa.

Este tercer circuito es muy similar al primer circuito, sin embargo, en este caso se tiene dos voltajes de entrada, ambos con una corriente alterna iguales y dos resistencias distintas, con esto podemos realizar un análisis de nodos y se cumple lo mismo en el circuito 1, de que la resistencia en paralelo con el amplificador es mayor que la resistencia que contribuye voltaje.
###   Preguntas
1. Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.

Pueden influir los siguientes parámetros:

Tensión de entrada diferencial: Esta es la tensión máxima que puede aplicarse entre los terminales de entrada sin problemas de corriente.

Rango de Temperatura: Es el rango de temperatura en el cual el dispositivo funciona.

Tensión de alimentación: Tensión de alimentación máxima que puede aplicarse al amplificador.

2. Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.

Otros de los amplificadores operacionales más comunes son: Amplificador de instrumentación INA125, OpAmp LM258, Op-Amp MC1741, TL081 y TL084.

- Amplificador de instrumentación INA125.

Este amplificador se alimenta con 12V, se lo utiliza para el manejo de una celda de carga. La ganancia del INA125 puede ser ajustada mediante un potenciómetro conectado a sus terminales. Toca tomar en cuenta que al cambiar la lontigud de las conexiones o alterar la fuente de alimentación puede desconfigurar la ganancia de este amplificador.

- TL084
Este amplificador es de alta velocidad , tiene una entrada de alto voltaje, tiene transistores bipolares, cuenta con una alta velocidad de respuesta,tiene una frecuencia interna de compensación y cuenta con salida de protección contra cortos circuitos.

- OpAmp LM258
Este es un amplificador operacional dual con alta ganancia con compensación de frecuencia.

- Op-Amp MC1741
Este amplificador operacional fue diseñado para utilizarse como amplificador sumador, integrador y en función del Componentes de retroalimentación.

- TL081
Este amplificador está diseñado con altas velocidades de rotación , baja polarización de entrada y las corrientes compensadas , y bajo coeficiente de temperatura.


3. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.

El amplificador operacional es un componente fundamental de la instrumentación electrónica moderna. Se utiliza extensamente en muchos dispositivos, junto con resistores y otros elementos pasivos. Entre las numerosas aplicaciones prácticas se encuentran amplificadores para instrumentos, convertidores digitales-analógicos, computadoras analógicas, cambiadores de nivel, filtros, circuitos de calibración, inversores, sumadores, integradores, diferenciadores, restadores, amplificadores logarítmicos, comparadores, elementos rotatorios, osciladores, rectificadores, reguladores, convertidores de tensión a corriente, convertidores de corriente a tensión y recortadores.
### CONCLUSIONES

- La configuración de los amplificadores operalacionales se adaptan a nustras necesidades en el circuito. La mayor utilidad del amplificafor operacional encontrada en el informe  es la capacidad al tomardatos o una señal extremadamente débil y aumentar su señal dependiendo la cantidad de veces que lo permita el amplificador operaconal.
- En base a la teoría y la practica se concluyo que un circuito básico para un amplificador operacional cumplen a más detalle los parámetros establecidos que un circuito complicado; y a su vez observamos la diferencia entre un circuito inversor y no inversor, en donde podemos notar que el circito inversor la señal de salida es diferente a la de la entrada con un desfase de aproximadamente 180°, en cambio un circuito no inversor la señal será la misma tanto para entrada como salida.
- Mediante práctica y teoría se ha comprendido el funcionamiento básico de un amplificador Operacional, el conocimiento requerido como saber a cerca de las configuraciones de las operaciones en los amplificadores, sus elementos eléctricos, la utilización en diseño de algunos productos eléctricos, etc.


### BIBLIOGRAFÍA

- Floyd, T. L. (2021). Principios De Circuitos Electricos C/Cd Rom (Circuitos ed., Vol. 8) [Libro electrónico]. PRENTICE HALL/PEARSON. http://media.espora.org/mgoblin_media/media_entries/1455/Principios_de_circuitos_electricos.pdf
