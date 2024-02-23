# calculadoraformato
Calculadora simple con salida formateada para mostrar separador de miles

Este es un proyecto sencillo donde se crea una calculadora que suma dos numeros ingresados por teclado y muestre el resultado con formato de separador de miles

~~~python
"""
Este es un programa que recibe dos valotes por teclado
suma los valores recibidos
muestra el resultado
en caso de ser el resultado mayor de 1.000
    muestra el resultado con formato de separador de miles
"""

# Se solicitan los operandos para sumarlos
x = int(input("Ingrese el valor de x: "))
y = int(input("Ingrese el valor de y: "))

# Se guarda el resultado en una variable
z = x + y

# Se muestra el resultado de la suma con formato de separador de miles
print(f"El resultado es: {z:,}")
~~~
