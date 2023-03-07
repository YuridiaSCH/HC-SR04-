# HC-SR04 Ultrasonic Distance Sensor

![](https://m.media-amazon.com/images/I/61PwZuGndiS.jpg)

## ¿Que es? 
> Sensor de distancia de bajo costo, su uso es muy frecuente en la robótica, utiliza transductores de ultrasonido para detectar objetos en un rango de 2 a 450 cm.

## Destacado por:
> Bajo consumo.

> Gran precisión y bajo precio por lo que esta reemplazando a los sensores polaroid en los robots mas recientes.

> Fácil uso. 

> Programación con las placas de desarrollo.

## ¿Como Funciona este Sensor?
> Incorpora un par de transductores de ultrasonido que se utilizan de manera conjunta para determinar la distancia del sensor con un objeto colocado enfrente de este. 
> Un transductor emite una “ráfaga” de ultrasonido y el otro capta el rebote de dicha onda.

> El tiempo que tarda la onda sonora en ir y regresar a un objeto puede utilizarse para conocer la distancia que existe entre el origen del sonido y el objeto.

![](![image](https://user-images.githubusercontent.com/124212145/223572634-fdb17c51-5c60-4b3d-8805-91d0c12afb68.png) 

<strong> El Sensor HC-SR04 cuenta con dos transductores ultrasónicos y con 4 terminales de conexión: </strong>

> GND: Alimentación negativa. 

> ECHO: Pin para mandar la señal ultrasónica.

> TRIG: Pin para recibir el rebote de la señal ultrasónica. 

> VCC: Alimentación positiva. 

## <strong> Formula para Calcular la Distancia en la que se Encuentra el Objeto </strong>
 > Distancia = ( Tiempo_medido ) * (velocidad_del_sonido) / 2
 
 <strong> En donde la Velocidad del Sonido es de 343m/s o 0,034cm/ms. </strong>


Pagina de ayuda: https://blog.330ohms.com/2021/12/28/tutorial-8-de-raspberry-pi-pico-sensor-ultrasonico/

https://blog.330ohms.com/2020/06/17/como-conectar-un-sensor-ultrasonico-a-raspberry-pi/#:~:text=El%20sensor%20HC%2DSR04%20nos,rebote%20de%20la%20se%C3%B1al%20ultras%C3%B3nica

https://www.murkyrobot.com/guias/sensores/hc-sr04#codigo

https://www.eneka.com.uy/robotica/sensores/sonido/m%C3%B3dulo-sensor-de-distancias-hc-sr04-detail.html#:~:text=El%20HC%2DSR04%20es%20un,encargada%20de%20hacer%20la%20medici%C3%B3n.
