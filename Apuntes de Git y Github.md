# Cuaderno digital Miguel

-[**Cuaderno Miguel**](http://www.github.com/miguelbayon)


# Apuntes de Git y Github
Comando necesario:  git --version

Comando para crear una carpeta git: git init

Comando para añadir los cambios: git add .

Comando para comprobar la estado carpeta: git status

Comndo para realizar un commit: git commit -m '......'

Comando para ver los commits existentes: git log

Subir al github:  

                  git remote add origin https://github.com/ale2fernandez2003/.primer-programa-en-java.git

                  git push -u origin master
 
 Comando para subir a github: git push -u origin master
 
 Ver repositorios remotos: git remote -v
 
-[**Listado commits**](https://i.imgur.com/mH5Ak8H.png)

-[**URL del ultimo commit**](https://i.imgur.com/y5EbzxZ.png)

# Clonar repositorio
Comando para clonar un repositorio git: git clone ....

Comando para clonar en un lugar especifico: git clone (URL repositorio) (lugar donde quieres clonarlo)

-[**Error**](https://i.imgur.com/HZ1uIpw.png)
(El error se debe a que no tengo permisos del creador original para poder editr su repositorio)

-[**Comando para subir repositorio al github**](https://i.imgur.com/O9rfHJF.png)
(Se usa de otra manera porque ya existe una URL origin)

-[**Captura de mi primer repositorio**](https://i.imgur.com/UiKQHnX.png)

-[**Comando para vincular el repositorio1**](https://i.imgur.com/fwvZ0SU.png)

-[**Captura de mi segundo repositorio**](https://i.imgur.com/g8IQiej.png)

-[**Comando para vincular el repositorio2**](https://i.imgur.com/B7WmhaG.png)

-[**Repositorios vinculados**](https://i.imgur.com/4iwPgfN.png)

# Usar BLUEJ
-[**Apuntes java**](https://github.com/ale2fernandez2003/java.git)

-[**Interfaz de BlueJ**](https://i.imgur.com/ek6BzaB.png)

-[**Circulos diferentes**](https://i.imgur.com/yEHpP61.png)

-[**Un cambio**](https://i.imgur.com/HnXeUbD.png)

-[**Casita**](https://i.imgur.com/xh5b71W.png)
(El estado de un objeto se refiere al conjunto de atributos y sus valores en un instante de tiempo dado. El comportamiento de un objeto puede modificar el estado de éste. Cuando una operación de un objeto modifica su estado se dice que esta tiene "efecto colateral".)

Para crear la casita hay que crear un curculo yn triangulo y dos cuadrados, para que se den los colores es poner que el circulo sea "yellow", el triangulo sea "green", un cuadrado "red" y el otro cuadrado con un color que no detecte, despues seria ir moviendo de poco a poco hasta dar la forma que aparece en pantalla

-[**Editar el CODE PAD**](https://i.imgur.com/mfFYLhw.png)

-[**Estudio de bloque de código**](https://i.imgur.com/YxBJ6nU.png)
(se crean 4 figuras: dos cuadrados, un triangulo y un circulo)

 ## Editar el bluej

-[**commit en git**](https://i.imgur.com/TZc9sOF.png)

-[**commits en github**](https://i.imgur.com/mVI3Yiz.png)

-[**cosas combiadas**](https://i.imgur.com/xIwvIkE.png)
(lo que mas me costo fue el movimiento del sol, fue lo unico que me llevo tiempo)

-[**commit 2 en git**](https://i.imgur.com/k65NOky.png)

-[**commits 2 en github**](https://i.imgur.com/oKO3LC2.png)

-[**cosas combiadas 2**](https://i.imgur.com/Oz5OcHL.png)
(crear la nueva clase me costo)

-[**commit 3 en git**](https://i.imgur.com/Z3Q4Ptr.png)

-[**commits 3 en github**](https://i.imgur.com/iyeO31o.png)

-[**cosas combiadas 3**](https://i.imgur.com/FhcOdLg.png)

#### Clase DAM
-[**Captura 1**](https://i.imgur.com/vQyNpsq.png)

-[**Captura 2**](https://i.imgur.com/RRfcy9q.png)

-[**Captura 3**](https://i.imgur.com/mZ7rnPv.png)

-[**Captura 4**](https://i.imgur.com/xcoGRzE.png)

#### Maquina-Expendedora-Simple

¿Se puede crear una máquina con un precio de billete negativo?

Si se puede

¿Qué valor devuelve la máquina si consultamos el balance del cliente actual después de haber impreso el billete?

El valos es 0

¿Qué sucede si invocamos el método imprimirBillete sin haber metido la cantidad de dinero correspondiente al precio del billete?

Que lo imprime

¿Qué sucede si introduces más dinero del precio del billete e imprimes un billete?

Que recoje el dinero y el balance es 0

¿Se puede introducir en la máquina cantidades negativas de dinero?

Si se puede 

¿Podemos introducir céntimos de euro en la máquina expendedora?

No se puede introducir centimos 

-[**Imagen Codigo**](https://i.imgur.com/iiKkzso.png)

-[**Captura 1**](https://i.imgur.com/Ee4Mcsv.png)
Los atributos son 5 y son: el precio, el balance y el origen de las estaciones

-[**Captura 2**](https://i.imgur.com/yaBNEVo.png)
Los atributos son 2 y son: solo es el balance y la estacion de destino, el precio del billete(0), el precio total(0) y el origen(null) estan de forma implicita

Cuando creo un nuevo objeto me pide el precio del dinero, el origen y el destino y el origen no esta en el constructor 
 
-[**captura**](https://i.imgur.com/Q3HtcnT.png)"precioDelBillete" abarca el tiempo de ejecucion del constructor y el "precioBillete" abarca el tiempo que dura el objeto creado

-[**asignaciones**](https://i.imgur.com/H8ZNot9.png)
