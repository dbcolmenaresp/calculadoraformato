# calculadoraformato
Calculadora simple con salida formateada para mostrar separador de miles

Este es un proyecto sencillo donde se crea una calculadora que suma dos numeros ingresados por teclado y muestre el resultado con formato de separador de miles

Primeramente se solicitan los números por teclado, con los que se va a realizar el cálculo simple

~~~python
x = int(input("Ingrese el valor de x: "))
y = int(input("Ingrese el valor de y: "))
~~~

El resultado se almacena en una variable para su posterior procesamiento

~~~python
z = x + y
~~~

Se muestra el resultado de la suma con formato de separador de miles

~~~python
print(f"El resultado es: {z:,}")
~~~
