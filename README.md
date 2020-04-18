# Sistema de Encendido/Apagado Raspberry

###### Sistema de Encendido/Apagado de forma segura a través de botón

## Código

<hr>

> Con este código indicaremos a nuestra Raspberry que, serán utilizados los pines **5 y 6** de el sistema de Entradas/Salidas.

### Instalación
Permisos para ejecutar script
`sudo chmod +x install`

Ejecutar Script `./install`

### Desinstalación
Permisos para ejecutar script
`sudo chmod +x uninstall`

Ejecutar Script `./uninstall`

## Instalación de Botón

<hr>

> Será necesario ubicar los pines **5 y 6** de el sistema de Entradas/Salidas de la Raspberry para poder conectarlos a nuestro botón de push.

###### Diagrama de entradas/salidas
![](GPIO-Pinout-Diagram-2.png)

Posteriormente conectaremos los pines **5 y 6** a nuestro botón de push.

> Uno a cada terminal (patitas) del botón

> **Para este caso el botón de push es normalmente abierto**. En caso de que lo pregunte el personal de la electrónica de tu preferencia.

<img src="https://www.dipmecatronica.com.mx/wp-content/uploads/2018/08/PUSH-BUTTON-NA.jpg" alt="Boton de Push" width="180" height="180">

> **Sí la Raspberry se encuentra apagada** el comportamiento del botón de push sera el siguiente:
>
> + Al presionar  el equipo arrancara de manera automática
>
> + Al volver a presionar se apagara de manera segura

> **Sí la Raspberry se encuentra encendida** el comportamiento del botón de push sera el siguiente:
>
> + Al presionar  el equipo se apagara
>
> + Al volver a presionar arrancara de manera automática



#### Recomendable conseguir 

###### Cables Dupont Jumper hembra-hembra
<img src="https://leantec.es/wp-content/uploads/2018/02/p_6_8_4_684-40-Cables-30cm-Hembra-Hembra-jumper-dupont-254-arduino.jpg" alt="Jumper" width="300" height="200">

###### Facilitarán las conexiones con tu Raspberry
<img src="https://foto.askix.com/upload/2/a7/2a772ae3f728cef25641b042fe2f963f.jpg" alt="Jumper" width="300" height="200">
