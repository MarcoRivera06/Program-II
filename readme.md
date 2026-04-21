# FOLDER

## Semana 2

## Class II: GitHub

## Comandos Linux

```bash

    clear -> limpiar la consola (ctrl + L)
    pwd → mostrar en qué directorio estamos
    exit -> salir de donde estamos trabajando
    touch -> crear un archivo vacio
    rm -> borrar un archivo
    ls -> listar archivos
    ls -a -> listar todo
    ls -l -> listar como lista
    echo -> crear un archivo con texto
    history -> historial de comandos hechos
    javac -> para ver si hay errores
    java -> compilar el archivo

```

## Primeros programas en Java

```java
public class Hi {

    public static void main(String[] args) {
        System.out.println("Hi, Celtic!");
        System.out.println("Hi, amo");
    }
}
```

```java
public class Sumar {

    public static void main(String[] args) {
        int a = 5;
        int b = 10;
        int suma = a + b;
        System.out.println("La suma de " + a + " y " + b + " es: " + suma);
    }
}
```

## cmd-git

```bash
      *** 1 vez ***
      git clone
      git init : una vez por prj

      *** cada día ***
      git satatus
      git add XXX / . :
      it comit -m "Creacion del prj"
      git push :
      git pull
```

## Clase III Prg II

1. Comand Palet -> ctrl + shift + P
2. Quick Open -> ctrl + P
3. Toggle Sidebar -> ctrl + B
4. Multi Select cursor -> ctrl + D
5. Copy Line shift + alt + up or shit + alt + down
6. Coment Code Block -> una linea ctrl + k + c varias lineas shift + alt + a <!-- uy a lo bien que fue  -->
7. Go back / move forward -> alt + --> or + ->
8. Show all symbols ctrl + T
9. Trigger suggestion or trigger parameter hints -> ctrl + space or ctrl + shit + space

## Project Inicial

## 📁 Estructura del Proyecto

```bash

├── assets/ #Carpeta destinada a recursos (imagenes, iconos, etc.)
├── .gitignore
├── Hi.class
├── Hi.java
├── Sumar.java
└── readme.md
```

## Imagen del proyecto

![Image](assets/image.png)

> [!NOTE]
> notas

Link
[https://github.com/MarcoRivera06/Program-II]

## Semana 3

## Java

Inicios de java

## Semana 4

Forma de solucionar problemas de programación

![Forma de solucionar problemas ](assets/FlujoSolucion.png)

Formas de optimización de código

Una forma de optimización es el uso de un operador terminario
Un operador ternario es un operador que tiene 3 partes (? : ;)

EJEMPLO

```java
//Normal
if (a>10)
      a = 100;
else
      a = -100;


// Optimizado (operador ternario)
a = (a>10) ? 100 : -100;

```

Para resolver problemas de programación lo ultimo que se tiene que hacer es programar, lo primero es tener una buena organización de los archivos o documentos del proyecto a desarollar, lo cual podemos modelar como un diagrama de las clases que tenemos o vamos a tener en DRAWIO.

EJEMPLOS

![Diagrama de clases](assets/Organizacion.png)
