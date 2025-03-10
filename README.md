[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/nYqVF7Kz)
# Trabajo Práctico 1

## Ejercicio 1

Para este ejercicio el objetivo es leer el código, anotar lo que piensen que los prints vayan a decir y luego correr el código para ver si les dio igual o no.

```python
i1 = 3
i2 = 5
i3 = i2 + i1
print("valor de i1:") #va a mostrar la frase: valor de i1:#
print(i1) #va a mostrar el valor de i1, o sea 3#
print("valor de i2:") #va a mostrar la frase: valor de i2:#
print(i2) #va a mostrar el valor de i2, o sea 5#
print("valor de i3:") #va a mostrar la frase: valor de i3:#
print(i3) #va a mostrar el valor de i3, o sea la suma entre i2(5) e i1(3), 8#
print(i1 + i2 + i3) #va a mostrar el resultado de la suma de los valores de i1, i2, e i3, o sea 16#

s1, s2, s3 = "Python", " is ", 'awesome'
print(s1 + s2 + s3) #va a mostrar la suma de estos 3 strings, lo que resulta en: "Python is awesome"#

x = y = z = "Naranja"
print("valor de x: " + x + ", valor de y: " + y + ", valor de z: " + z) #va a mostrar: valor de x: Naranja, valor de y: Naranja, valor de z: Naranja#

z1 = i3 / i2
print(z1) #8/5, o sea 1.6#
z2 = i3 % i2 
print(z2) #el resto de la division entre 8 y 5, o sea 3#
f1 = -.5
f2 = 10
f3 = f1 + f2
i3 = int(f3)
print("entero i3:") #va a mostrar la frase: entero i3:#
print(i3) #9#
print("variable f3:") #va a mostrar la frase: variable f3:#
print(f3) #9.5#
f2 += i1
print("el valor de") #va a mostrar la frase: el valor de#
print(f2) #va a mostrar el resultado de la suma de i1(3) y f2(10), o sea 13#
print("más") #va a mostrar la frase: más#
print(f1) #-0.5#
print("es:") #va a mostrar la frase: es:#
print(f2 + f1) #va a dar el resultado de la suma entre f2(13) y f1(-.5), o sea 12.5#

```

## Ejercicio 2 - Math

Escribir un programa dentro de exercise_math.py que dado dos números enteros imprima en pantalla el resultado de las siguientes operaciones: la suma, la diferencia, el producto, el promedio, el cociente entero y el resto de la división entera y el valor real de la división. Para entregar correctamente se deberá imprimir dichos resultados en el orden que fueron pedidos en la consigna. Por ejemplo, primero la suma, despues la diferencia, y asi sucesivamente.

Ejemplo: Para a = 57 y b = 7 el output debera ser:

```python
64
50
399
32.0
8
1
8.142857142857142
```


