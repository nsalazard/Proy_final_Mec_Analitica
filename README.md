# Proyecto final de Mecanica Analítica
Autor: Nicole Sofia Salazar Delgado

##Pendulo esférico:
Dado que fue uno de los problemas que resolvimos en uno de los talleres, me parecio una perspectiva interesante animarlo ya que por la pandemia no podemos ir al laboratorio a ver el comportamiento de los sistemas y tambien esta el hecho de que animado podemos hacer que la trayectoria que siga la partícula se vea más claramente e incluso podemos despeciar la fricción para que siga más de cerca las ecuaciones que resolvimos en el taller.

Se usa también RK4 que consiste en un método iterativo bastante popular de la familia los Runge–Kutta, que permite la evolución del sistema y donde su error acumulado es de orden 4.

Algo bueno de este programa es que podemos ir variando los valores de la masa, la longitud y la gravedad. Lo que nos permite explorar el sistemas y sus ecuaciones de movimiento.

## ¿ Como correr la animación?
Para crear y correr el programa use la aplicación de escritorio Pycharm, en esta cree un proyecto donde instale los paquetes necesarios como: numpy, pygame y math. Luego simplemente se guarda y usando la pestalla superior donde dice "run" deberia poder ejecutarse.

Esta es una imagen de la animación con los parametros (masa) m = 2.0, (longitud de la cuerda) l = 4.0 y (gravedad) g= 9.81


![PS_2_4_9 8](https://user-images.githubusercontent.com/61853949/132080885-0a28ce70-bd3a-4d40-b68d-5917befada38.PNG)

Podemos jugar cambiando los valores de los parametros y observando sus efectos en las animaciones. Por ejemplo si aumentamos la masa tal que m=4.0
![PS_4_4_9 8](https://user-images.githubusercontent.com/61853949/132080922-f44ba515-67a3-43f8-be73-77a93242c442.PNG)

O bien podemos tambien aumentar la gravedad a g = 20.0. En este caso el péndulo se mueve más rapido que en los casos anteriores
![PS_2_4_20 0](https://user-images.githubusercontent.com/61853949/132081021-871a0d9d-0771-4c28-b157-82bd08963dbc.PNG)


Y cuando disminuimos la gravedad a g=2.0, el péndulo se mueve muy lento
![PS_2_4_2 0](https://user-images.githubusercontent.com/61853949/132081103-bd3007f5-7e2c-49f4-a563-a5b9dd667c94.PNG)

En este caso como no hay fricción al haber más gravedad el pensulo se va a mover más rapido y podemos imaginarnos que si la gravedad es muy baja, entonces la partícula interactua debilmente con el campo gravitatorio.


