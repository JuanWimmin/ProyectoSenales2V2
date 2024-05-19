# ProyectoSenales2V2
DTMF detector using fft V2

¿Cómo ejecutar proyecto?

Método 1: Descargar el archivo completo. En caso de no querer clonar el repositorio con 'git' dirígete a la parte superior de esta página. Al costado derecha habrá un botón de color verde con el texto: 'code'. Al hacer click sobre este elemento emergerá una pequeña ventana, en la parte inferior de la misma habrá la opción "Descargar archivo compreso ZIP"

Una vez descargado, descomprir el archivo en la ubicación deseada y usando el software Matlab pararse sobre el archivo 'main.m' encontrado en la carpeta principal. Correr el script. En caso de que se desplieguen pantallas de advertencia, dar click en el botón 'Add Path' y ejecutar nuevamente.

Método 2: Clonar el archivo (Método sólo disponible si ya está instalado git en la máquina)

En la carpeta donde se desee guardar el archivo, abrir 'CMD' (Es posible usar shell también pero recordar que los comandos aquí explicados son para cmd) utilizar el siguiente comando: 'git clone https://github.com/FelipeRobot/proyecto_tratamiento_sennales.git'

Una vez clonado, descomprir el archivo en la ubicación deseada y usando el software Matlab pararse sobre el archivo 'main.m' encontrado en la carpeta principal. Correr el script. En caso de que se desplieguen pantallas de advertencia, dar click en el botón 'Add Path' y ejecutar nuevamente.

INSTRUCCIONES DEL PROYECTO _ PORFAVOR LEER CON ATENCION

*ScriptFFT.m** is the main entry of this application.

**enframe.m** is a function of third party toolbox 'voicebox'.
AUDIOPRUEBA Y AUDIOPRUEBA3.wav is audio file of DTMF tones for demonstration. 

If you want to detect your own DTMF sound files, you can modify the code：

    [x fs] = audioread('dtmf_sound.wav'); 

##P.S.
This project ignore the noise of the DTMF sound files， however as long as the SNR is good(or the noise is not too loud), it still can output correct results
