# Implementación Sistema Inteligente
[![Python](https://img.shields.io/badge/Python-3.7-blue?logo=python)](https://www.python.org) 

### Descripción 
La problemática surge de las situaciones que pueden suceder dentro de un
establecimiento, donde una persona porta algún arma atentando contra la integridad
de las personas presentes. La cual no es reportada de forma inmediata, ya sea por
que la misma pasa desapercibida o por que la persona encargada de revisar las
cámaras del sitio por distintos factores no está del todo atenta. Es por esto mismo
que se desarrollaría un modelo que logre detectar cuando una persona está armada
para poder tomar las medidas necesarias lo antes posible.

### Alcance
El alcance del mismo será la identificación de personas portando armas blancas
(cuchillos) y armas de fuego (pistolas).

### Objetivos
- Desarrollar un modelo que identifique la presencia de una persona que porta
un arma.
- Disminuir situaciones de inseguridad.

### Topologia
Para la topología de la red se decidió utilizar una red convolucional, debido
a su mayor rapidez de entrenamiento y su simpleza a la hora de poder
trabajar con imágenes. Por cada capa convolutiva se agregó una capa de
activación, en la cual se usó la función relu y cada cierta cantidad de capas
se agregaron capas “dropout” las cuales hacen que la red pierda
información aprendida para evitar el sobreentrenamiento. En las últimas
capas de la red se utilizó una capa de activación con la función softmax, la
cual es utilizada muy comúnmente para clasificación.
![Foo](https://i.ibb.co/h8CDwf4/Screen-Shot-2021-12-03-at-11-16-41-AM.png)
