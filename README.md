# Proyecto final de Mecanica Analítica
Autor: Nicole Sofia Salazar Delgado

## Pendulo esférico:

Dado que el péndulo esferico fue uno de los problemas que resolvimos en uno de los talleres, consideré que seria interesante animarlo ya que por la pandemia no podemos ir al laboratorio a ver el comportamiento de los sistemas. Además, al animarlo podemos ver la trayectoria sigue la partícula más claramente e incluso podemos despreciar la fricción para que cumpla las ecuaciones que encontramos en el taller.

Algo bueno de este programa es que podemos ir variando los valores de la masa, la longitud y la gravedad. Lo que nos permite explorar el comportamiento del sistema en diversas condiciones.

Aqui esta un video hecho con distintos valores para la masa, longitud y gravedad, podemos observar como estos influyen en la trayectoria del pendulo.
https://youtu.be/iE5TLGWmL0Y

## ¿ Como correr la animación?
Para crear y correr el programa use la aplicación de escritorio Pycharm, en esta cree un proyecto donde instale los paquetes necesarios como: numpy, pygame y math. Luego simplemente se guarda y usando la pestalla superior donde dice "run" deberia poder ejecutarse. 

Para la elaboración del programa usé RK4 que consiste en un método iterativo bastante popular de la familia los Runge–Kutta, que permite la evolución del sistema y donde su error acumulado es de orden 4. En referencia a la materia, se puede ver claramente en las primeras lineas del código que el péndulo sigue las dos ecuaciones diferenciales (una para theta y otra para phi) tal cual como las que hallamos apartir del lagrangiano.

Esta es una imagen de la animación con los parametros (masa) m = 2.0, (longitud de la cuerda) l = 4.0 y (gravedad) g= 9.81
![PS_2_4_9 8](https://user-images.githubusercontent.com/61853949/132080885-0a28ce70-bd3a-4d40-b68d-5917befada38.PNG)

Podemos jugar cambiando los valores de los parametros y observando sus efectos en las animaciones. Por ejemplo si aumentamos la masa tal que m=4.0
![PS_4_4_9 8](https://user-images.githubusercontent.com/61853949/132080922-f44ba515-67a3-43f8-be73-77a93242c442.PNG)

O bien podemos tambien aumentar la gravedad a g = 20.0. En este caso el péndulo se mueve más rapido que en los casos anteriores
![PS_2_4_20 0](https://user-images.githubusercontent.com/61853949/132081021-871a0d9d-0771-4c28-b157-82bd08963dbc.PNG)

Y cuando disminuimos la gravedad a g=2.0, el péndulo se mueve muy lento
![PS_2_4_2 0](https://user-images.githubusercontent.com/61853949/132081103-bd3007f5-7e2c-49f4-a563-a5b9dd667c94.PNG)

En este caso como no hay fricción al aumentar la gravedad el péndulo se mueve más rápido, ya que se podría pensar como cuando un planeta es muy grande por ejemplo Jupiter puede atraer fuertemente a una particula y por otro lado si la gravedad es muy baja, entonces la partícula interactua debilmente con el campo gravitatorio, como en la ISS donde las cosas se moverian casi solo por la fuerza que se les dió al inicio




