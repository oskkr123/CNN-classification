<p align="center"><img src="https://drive.google.com/open?id=1fVCi-TM6GigEmhX1oYgKEO870MECuTuA" width="1500" heigth="500"></p>

# Reconocimiento de actividades en video utilizando un descriptor de covarianza local
### Oscar Mauricio Mendoza Casas



*Universidad Industrial De Santander* </br>
*Ingenieria de sistemas*</br>
*2019*</br>
<p align="center"><img src="http://garza.uis.edu.co/idayregreso/images/logoUIS.jpg" width="342" heigth="166"></p>

<p align="center"><img src="https://storage.googleapis.com/kaggle-competitions/kaggle/5048/media/drivers_statefarm.png" width="1500" heigth="500"></p>

# Introduccion

El reconocimiento de actividades tiene una gran aplicabilidad en multiples areas y escenarios de la vida cotidiana, como la video-vigilancia, el analisis deportivo, los sitemas de interaccion hombre computador, entre muchos otros.

En los ultimos siete años las denuncias por robos contra ciudadanos se elevaron un 76% en bucaramanga, al mes de junio la policia metropolitana ha capturado a mas de ademas de 4500 capturas por diferentes delitos, aproximadamente 1000 de estas capturas por hurtos, que pueden ser evitados o documentados mas efectivamente con la ayuda de una herramienta de clasificacion de acciones o reconocimiento de actividades, que pueda ser un apoyo para la revision del material para evidencia a la hora de hacer denuncias.

El enfoque de este proyecto no esta planteado para ningun caso en especifico, sin embargo se hace mencion a una de las posibles aplicaciones, el proyecto consiste en la realizacion de un descriptor basado en el calculo de la covarianza local de caracteristicas densas, estas caracteristicas, pueden ser precalculadas localmente, o pueden ser extraidas de alguna red neuronal de la literatura, acutalmente se utiliza la CNN llamada ResNet para la extraccion de estas caracteristicas en la realizacion del descriptor.

Actualmente se trabaja sobre el dataset UT interactions, que consta de 6 acciones diferentes cada una con 10 videos, las acciones son las siguientes:

    0: Hand Shaking - Apreton de manos
    1: Hugging - Abrazo
    2: Kicking - Patear
    3: Pointing - Apuntar
    4: Punching - Puñetazo
    5: Pushing - Empujar


# Objetivo

-Clasificar las Acciones resultado de la interaccion entre dos personas, o un sujeto individual

-Proponer un metodo de clasificacion de acciones generalizado basado en covarianza, que genere informacion sobre puntos de interes(locales).

-Aplicar los métodos vistos en las clases de Visión por Computador.

# Aplicaciones posibles

-Video vigilancia.

-Analisis deportivo.

-Herramienta de apoyo para las autoridades.

-Sistemas de alerta por deteccion de actividades.



# Referencias
Dataset UT interactions
-http://cvrc.ece.utexas.edu/SDHA2010/Human_Interaction.html

# Repositorio
-https://github.com/oskkr123/Computer-vision
