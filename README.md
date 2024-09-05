# Practica_1

## Integrantes
- Uriel Vladimir Alvarez Tapia 20121191
- Miguel Angel Castañeda Garcia 20120015
- Diana Alejandra Mendoza Mendoza 20121226

## Introducción 
En el marco de las actividades orientadas al aprendizaje de robots industriales, se realizó una práctica centrada en el manejo y los comandos básicos de movimiento de un robot EPSON C4, un modelo de seis ejes que destaca por su alta velocidad y flexibilidad. Este robot, diseñado para operar en espacios reducidos, cuenta con una capacidad de carga útil de hasta 4 kg y tiempos de ciclo de tan solo 0,37 segundos, lo que lo convierte en una herramienta ideal para aplicaciones en industrias como la automotriz, electrónica, médica y alimentaria [1].

Durante la práctica, se trabajó con los movimientos Move y Go, los cuales constituyen dos de los comandos fundamentales del robot. El comando Move permite realizar trayectorias continuas con alta precisión, mientras que el comando Go ejecuta movimientos rápidos y directos, mejorando el tiempo de ciclo en tareas repetitivas [2]. Estas actividades permiten profundizar en el control del robot, destacando su precisión y adaptabilidad para optimizar procesos en diversas aplicaciones industriales.

## Instrucciones
### Instalar el programa EpsonRC+ correctamente
Tras realizar la correcta instalación del programa se genera un icono como el que se muestra en la Figura 1:
![image](https://github.com/user-attachments/assets/1c417684-2da6-44bc-bea4-d755f8309722)

Al abrir el programa se presenta la siguiente pantalla Figura 2:
![image](https://github.com/user-attachments/assets/81e8e554-26be-4a92-bb3d-ca4981d28316)

En esta pantalla, se puede crear un nuevo programa. Es importante seleccionar *C4 sample* a la hora de crear el programa Figura 3
![image](https://github.com/user-attachments/assets/55b7db83-1842-4edc-a23b-08508cd5fffb)

Una vez creado el programa, desde la ventana de *Herramientas/Tools* se abre la funcion *Robot Manager*, asi como *simulation* para abrir la ventana de control de robot al igual que la ventana de simulacion del robot Figura 4.
![Imagen de WhatsApp 2024-09-04 a las 20 32 20_69a69b1a](https://github.com/user-attachments/assets/dc639006-2ce4-4f3a-bfe3-a90af4251b43)

En la figura 5, se muestran ambas pestañas abiertas. A la izquierda la de *Robot Manager* y a la derecha la de *Simulator*
![Imagen de WhatsApp 2024-09-04 a las 20 35 06_bd721ae6](https://github.com/user-attachments/assets/333b144e-3dd5-41c5-afc3-ded84c8b9b38)

Una vez activados los motores, se puede proceder a accionar al motor.

### Conexión al Robot Epson C4

La conexion al robot, se realiza mediante el puerto USB que permite que el accionamiento del robot fisico, desde la ventana de *Robot Manager*

### Conocer las partes del robot
El robot Epson C4 (Figura 6) cuenta con 6 grados de libertad lo que permite tener un gran alcance sobre las tareas que realice. 
Además, este modelo es capas de soportar una carga útil de hasta 4 kg.
Los servomecanismos están basados en tecnología QMEMS que minimiza las vibraciones del sistema y maximiza la aceleración y desaceleración del mismo; recalcar que todos los ejes tienen un mecanismo de frenado para un mejor control. 
El Epson C4 cuenta con un tiempo de ciclo de 0.47 s y tiene un peso aproximado de 29 kg.
![image](https://github.com/user-attachments/assets/3e4e527b-8ebf-495f-80af-9aa7c63b213b)


### Movimiento del robot en World y Joint
El movimiento tipo Joint permite la libertad a las articulaciones del robot; dando paso a las rotaciones del mismo. Cada eje puede rotar de forma individual en dirección positiva o negativa; dicho movimiento es medido en grados. Figura 7:

![Imagen de WhatsApp 2024-09-04 a las 20 35 21_d247808d](https://github.com/user-attachments/assets/a8c9534c-8468-4e0b-8584-7b68b2941294)

Por otro lado, el movimiento tipo Word emplea un sistema de coordenadas cartesiano (generalmente tridimensional) que se encuentra sobre un punto de la unidad mecánica. Este tipo de movimiento permite desplazamiento de los eslabones para diversas configuraciones de forma global, considerando el  ultimo elabon como el punto de referencia. Figura 8
![image](https://github.com/user-attachments/assets/4ab93b8b-4ffb-4301-ba62-a7dac2833a5f)


### Analizar las diferencias

## Conclusiones
- **Uriel Vladimir Alvarez Tapia:** Esta practica permitio la comprension basica del funcionamiento del robot EPSON C4, asi como su control a travez de su respectivo software de programacion EPSON RC+. El software antes mencionado permite el control en sistema *WORLD* y *JOINT, habilitando una versatilidad en su programacion de acuerdo a las necesidades de su uso. Permitiendo su utilizacion en distintas aplicaciones.
Ademas, la herramienta de simulacion del software presenta una especial utilidad en la prueba de programas, permitiendo prevenir colisiones durante el movimiento manual o programao del equio y salvaguardando la integridad del mismo.
- **Miguel Angel Castañeda Garcia:** El software Epson RC+7.0 resultó de mucha utilidad para el control de movimientos (joint y word) para el modelo del robot del laboratorio. Además, recalcar que, la interfaz gráfica de botones facilita el aprendizaje del mismo.
El robot Epson es útiles para diversas aplicaciones, por ejemplo, la manipulación de objetos de peso considerable, y para trabajos donde de requiera bastante precisión.
El punto clave de cualquier tipo de control recae sobre el control que se tenga del mimo.
- **Diana Alejandra Mendoza Mendoza:** La práctica realizada con el robot EPSON C4 permitió un acercamiento práctico a las capacidades de control y programación de un robot industrial de seis ejes. A través del uso de los comandos Move y Go en el entorno EPSON RC+, se comprendió su importancia para ejecutar movimientos precisos y rápidos, lo que optimiza considerablemente los tiempos de ciclo en tareas repetitivas. Además, el diseño que tiene el C4 y su capacidad para operar en espacios reducidos mostraron su versatilidad en entornos de producción automatizados. La práctica fue muy importante para comenzar el aprendizaje sobre la manipulación de robots industriales y su aplicación en el ámbito de la mecatrónica, resaltando las oportunidades que ofrece la robótica en la optimización de procesos productivos.
## Referencias
[1]
R. Epson, “Robot Epson C4L - 6 ejes de largo alcance | Productos | Epson México,” Epson.com.mx, 2024. https://epson.com.mx/Para-el-trabajo/Rob%C3%B3tica/6-Ejes/Robot-Epson-C4L---6-ejes-de-largo-alcance/p/RC4-A901ST73-W#:~:text=Industrias%20que%20lo%20utilizan&text=Pueden%20utilizarse%20para%20una%20amplia,en%20miles%20de%20distintas%20aplicaciones. (accessed Sep. 05, 2024).

[2]
“Manual del usuario Administración y desarrollo de proyectos.” Available: https://files.support.epson.com/far/docs/epson_rc_pl_70_users_guide_spanish_(v73r2).pdf


