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

- [**captura 1**](https://i.imgur.com/N0tO7Gr.png)

- [**captura 2**](https://i.imgur.com/326Rowq.png)

#### Pseudocódigo
ejemplo:

```java
  if(apruebo){
    obtendre un premio
    
  }
  
  else{
    obtendre un castigo
    
  }
```
El pseudocódigo es una forma de escribir los pasos que va a realizar un programa

#### Operadores relacionales

| Operando 1 | Operador | Operando 2 | Significado       |
|------------|----------|------------|-------------------|
| a          | <        | b          | menor que         |
| a          | >        | b          | mayor que         |
| a          | <=       | b          | menor o igual que |
| a          | >=       | b          | mayor o igual que |
| a          | ==       | b          | igual que         |
| a          | !=       | b          | distinto que      |


```java
  if(a+b==a*b-740){
    invita a copas;
    
  }
  
  else{
    invita a chupitos;
    
  }
```
### Estudiando la instrucción condicional de introducirDinero

En el "if" tiene que ser un valor igual o mayor que 1 y no nos saldra ningun mensaje a demas que en el balance aparecera el numero que hemos introducido.

Si no se da el caso anterior entonces sera un "else" por lo que pondra un mensaje diciendonos que el valor no es aceptado.

Y si introducimos el numero "0" entonces nos saldra el mismo mensaje que si fuera un else.

### Diferencias maquinas expendedoras

-[**captura**](https://i.imgur.com/4zCO21A.png)

en la mejorada gasta solo lo que vale el billete y en la simple quita todo el dinero que tenia en el balance 
en el balance del cliente ahora te devuelve lo que te falta despues de imprimir y no es como antes que devolvia el numero 0


-[**Método imprimiBillete sin parte else**](https://i.imgur.com/uU7lDEN.png)

no imprime al no ejecutarse


### Investigando cómo escribir la instrucción condicional

```java
if (calificacion<5){
  me castigaran 
  
}
```

```java
if (no como){
  tengo hambre
  
}

else{
  ya no tengo hambre
  
}
```

```java
if (calificacion<4.99) {
  obtendre castigo

}

else if (calificacion==10) {
  obtendre un premio

}

else {
  aprobare

}
```

-[**captura**](https://i.imgur.com/Ky2CDhu.png)

Indentar significa hacer espacios hacia la derecha para mover una línea de código, lo podés hacer usando la barra espaciadora o con la tecla de tabulación

-[**mal identado**](https://i.imgur.com/h8ORC2q.png)

### Corregir codigo 

```java
void temperaturaMaximaMensual(int array[]) {
  int tmp=0;
  String cad="";
  int array2[] = new int[MAX];
  
  for(int i=0;i<array.length;i++) {
    array2[i]=array[i];
  } 
  int k=0,x=0,c=0;
  
  for(int i=1;i<array2.length;i++) {
    if(array2[i-1]<array2[i]) {   
      x=i;
      c++;    
    }
    else {
      x=0;
      for(int j=0;j<array2.length-i;j++) {
       if(array2[j]>array2[j+1]) {
         k=array2[j+1]; 
         array2[j+1]=array2[j]; 
         array2[j]=k;
       } 
      }
    }
    JOptionPane.showMessageDialog(null,"La temperatura: "+array2[MAX-1]+" Día: "+(x-1));
  }
}
```
-[**captura1**](https://i.imgur.com/drZrIyK.png)

-[**captura2**](https://i.imgur.com/kfpvjCz.png)

-[**diferentes formas**](https://i.imgur.com/44Gcm6e.png)

-[**calculos**](https://i.imgur.com/QbjuTwk.png)

Se usa para dividir dos números y devuelve solo el resto.

```java
8 + 2 * 2
  12   (int)
4 - 6 / 2
  1   (int)
 ```
en los calculos matematicos tienen preferencia las multiplicaciones y las divisiones sobre las sumas y las restas 
