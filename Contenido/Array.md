[Regresar...](../README.md)
# Array o listas - Python

## Crear Array:
````py
Lista = [] # Array Vacío
````
Array con elementos:
````py
Lista = ["Hola0", "Hola1","Hola2", "Hola3"] # Array con elementos iguales
Lista = [False, False,True, False]          # Array con elementos iguales
Lista = [2534, 541,48, 5]                   # Array con elementos iguales
Lista = [False, "String", 45, 2.1545]       # Array con datos Variados
````

## Imprimir Array:
Se debe tener en cuenta que el número de indice de cada elemento empieza con el 0:
<p align="center">
    <img src="https://i.imgur.com/gCtkHJS.png">
 </p>

````py
# Imprimir elementos desde intervalos especificos
print(Lista[2:4]) 

# Imprime elementos desde la posición 0, hasta una posición especifica
print(Lista[:3])

# Imprime desde un elemento espeficicado hasta el final
print(Lista[3:]) 

# Imprime Toda la lista
print(Lista[:])       
````

## Insertar elementos
````py
# Agrega un valores al final
Lista.append("")     

#Agrega varios valores 
Lista.extend(["valor1","valor2", "valor3"])   #Agrega más valores

# Agregar valor en una posición especifica
Lista.insert(2,"New valor")   
            # Argumento[0] = Número de posición donde se insertará el valor
            # Argumento[1] = Valor (puede ser int, string, bool, etc)
````
## Imprimir posición de un elemento:
````py
# Imprime el indice de un elemento especificado
print(Lista.index("Valor5"))   # Muestra dónde se encuentra el valor, desde izquierd a derecha  
````
## Comprobar elemento existente :
````py
print("hola2" in Lista)   
# Imprime un true si se encontró dicho elemento dentro de un Array
# Imprime un False si se no encontró dicho elemento dentro de un Array
````
## Sumar o juntar Arrays :
````py
Lista1 = [1,2,3,4,5,6,7,8,6,7,8,9]
Lista2 = ["dato1", "dato2", "dato3"]
Lista3 = [Lista1 + Lista2]              # se juntaron elementos
````


