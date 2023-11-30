# Introducción a la programación

Ejercicios en JavaScript en VSC. 
Programa de Formación Digital "Conecta Empleo" - Fundación Telefónica


Módulo 1. Fundamentos de la programación
  - Ejercicio 1.
      - Los años bisiestos que habrá antes de 2050
      - Cuántas cartas con número par y negras hay en una baraja de poker
   
  - Ejercicio 2. Define una variable cuyo valor sea una cadena que represente una carta de la baraja. Recuerda que representamos las cartas con una cadena formada por un número que representa el valor, seguido de una letra que representa el palo. Ahora crea otras dos variables que representan a la carta anterior y a las carta posterior en una baraja ordenada. Finalmente, crea una última variable que concatene las cadenas de las 3 cartas anteriores usando las variables que ya tienes.


  - Ejercicio 3. Define una variable cuyo valor sea una cadena que represente una carta de la baraja, cuyo valor sea mayor que 9. Ahora utiliza el operador para indexar la cadena, y accede al palo de la carta. ¿Cuál es la diferencia si la carta tiene un valor menor o igual que 9?



Módulo 2. Estructuras de control
  - Ejercicio 1. Programa un ejemplo que, dada una variable de tipo cadena con la carta del 4 de corazones, compruebe si es de corazones y además es el número 4. En caso afirmativo, lo imprimimos en la consola. Probamos el mismo programa con el 3 de corazones, y con el rey de corazones. ¿Qué sucede?
   
  - Ejercicio 2. Utiliza un bucle para recorrer todos los años bisiestos anteriores a 2050, e imprímelos en la consola.

  - Ejercicio 3. Utiliza un bucle para recorrer todas las cartas de la baraja, desde el 1 al 12 de cada palo. Imprime en pantalla solamente las cartas rojas que sea múltiplos de 3.


Módulo 3. Estructuras de datos
  - Ejercicio 1. Programa un ejemplo que almacene en un array todas las cartas de la baraja, cada una representada con un diccionario que tenga un palo y un valor.

  - Ejercicio 2. Partiendo del array que has construido en el ejercicio anterior, construye un algoritmo que filtre en un nuevo array sólo las cartas rojas, y en otro array las cartas negras.

  - Ejercicio 3. Partiendo del array que has construido en el ejercicio anterior, construye un algoritmo que filtre en un nuevo array las cartas rojas y pares. Luego imprime en la consola la última carta de ese nuevo array.



Módulo 4. Funciones y programas
  - Ejercicio 1. Desarrolla una función que puntúe una mano de cartas, que tenga como parámetro un array de cartas, cada una representada por un diccionario con palo y valor. Al puntuar, las cartas suman su valor excepto si es un as que suma 20. Prueba a invocarla con varias manos de cartas con y sin ases.

  - Ejercicio 2. Partiendo de la función anterior, modíficala para que además las cartas rojas sumen el doble. Prueba a invocarla con varias manos de cartas.

  - Ejercicio 3. Desarrolla un programa que use la función anterior para puntuar las manos de cartas de dos jugadores e imprima por consola al ganador, es decir, al que obtenga mayor puntuación.


Módulo 5. Librerías de código
  - Ejercicio 1. Desarrolla una librería Croupier que tenga una función para barajar cartas. Para barajar, intercambiamos una carta aleatoria dentro de nuestra baraja por otra. Y esto lo hacemos 100 veces. Se recomienda usar la librería Math.random. Por ejemplo, intercambiar la carta en la posición 7 por la carta en la posición 24.
    
  - Ejercicio 2. Desarrolla nuevas funciones de la librería Croupier: Repartir, que toma la carta en primera posición de la baraja y la elimina del array Puntuar que, dada una mano de 4 cartas sume su valor. Pero si todas las cartas son iguales, multiplica el valor por 10.

  - Ejercicio 3. Desarrolla una librería Calculadora que calcula las longitudes de varias figuras geométricas como cuadrados, rectángulos y círculos.


Módulo 5. Objetos
  - Ejercicio 1. Desarrolla un objeto Croupier que tenga como datos una baraja de cartas completa. Y puntuaciones especiales para el as y las figuras (jota, dama y rey).

Jota = 12

Dama = 14

Rey = 17

As = 20
    
  - Ejercicio 2. Añade al objeto una función para tomar 5 cartas aleatorias de la baraja. Y luego para puntuar esa mano de cartas con las puntuaciones especiales.
