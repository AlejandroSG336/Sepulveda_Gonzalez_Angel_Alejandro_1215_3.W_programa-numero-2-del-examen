# Sepulveda_Gonzalez_Angel_Alejandro_1215_3.W

# Descripción:
# Este programa solicita al usuario tres números, los guarda en variables (A, B, C), y determina cuál es el mayor y cuál es el menor.
# Si los tres valores no son distintos, se muestra un mensaje de error y el programa termina.

# Solicitar la entrada de tres números distintos
print("Ingresa tres números distintos")

# Convertimos la entrada a números a int o float

a = float(input("Ingresa número A: "))

b = float(input("Ingresa número B: "))

c = float(input("Ingresa número C: "))

# Validar si los números son distintos

if a == b or b == c or a == c:

# Si algún par de valores es igual, se muestra este mensaje
    
print("Error: Los tres números deben ser distintos.")

else:

# Mostrar los valores ingresados
    
print(f"Valores ingresados: A = {a}, B = {b}, C = {c}")

  # Determinar el mayor y el menor utilizando las funciones max() y min()
  
  mayor = max(a, b, c)    
  
  menor = min(a, b, c)

  # Mostrar los resultados
  
  print(f"El número mayor es: {mayor}")
  
  print(f"El número menor es: {menor}")

![image](https://github.com/user-attachments/assets/811d8ed9-cf5e-49a8-9715-768d3e4fb7f6)
![image](https://github.com/user-attachments/assets/351fe12c-e0c5-46a9-a59c-b9c8fb6e6308)
