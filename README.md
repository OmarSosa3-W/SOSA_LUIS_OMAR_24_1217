# SOSA_LUIS_OMAR_24_1217

# PROGRAMA 1:
def max_in_list(numeros):
    return max(numeros)

# Ejemplo
print(max_in_list([5, 12, 8, 20, 15])) 

![image](https://github.com/user-attachments/assets/630de702-a6f5-45ab-b0b3-511118fd7c07)
![image](https://github.com/user-attachments/assets/60506eb4-e9d9-4799-a000-5494109d261d)

# PROGRAMA 2:
def mas_larga(palabras):
    return max(palabras, key=len)

# Ejemplo
print(mas_larga(["hola", "aventura", "programación", "chat"]))  

![image](https://github.com/user-attachments/assets/edc8cb14-a60c-4cce-8009-bb4a708977b0)
![image](https://github.com/user-attachments/assets/3afd62a8-5c9a-455d-bb04-03476f8e9e1f)

# PROGRAMA 3:
def filtrar_palabras(palabras, n):
    return [palabra for palabra in palabras if len(palabra) > n]

# Ejemplo
print(filtrar_palabras(["hola", "aventura", "casa", "programación"], 5))  

![image](https://github.com/user-attachments/assets/822422e6-dc45-4a4e-8214-ee670568620f)
![image](https://github.com/user-attachments/assets/d649ca48-f2cf-4500-8064-deed472b875c)

# PROGRAMA 4:
def contar_mayusculas(cadena):
    return sum(1 for letra in cadena if letra.isupper())

# Ejemplo
cadena = input("Ingresa una cadena: ")
print("Número de letras mayúsculas:", contar_mayusculas(cadena))

![image](https://github.com/user-attachments/assets/b02ca13e-703e-4e73-bf40-566cfd5f9ddd)
![image](https://github.com/user-attachments/assets/c5caef5b-5c22-4e8e-bb5d-c73197c3c5b7)

# PROGRAMA 5:
def binario_a_entero(binario):
    return int(binario, 2)

# Ejemplo
print(binario_a_entero("1101"))  


![image](https://github.com/user-attachments/assets/72b9a461-9fc9-4b9b-ab9b-d10b8cebfae5)
![image](https://github.com/user-attachments/assets/07d273b9-5c26-45de-846f-5e1dc34f63bc)

# PROGRAMA 6:
def calcular_edades():
    anio_actual = int(input("Ingresa el año en curso: "))
    for _ in range(3):
        nombre = input("Nombre: ")
        nacimiento = int(input(f"Año de nacimiento de {nombre}: "))
        edad = anio_actual - nacimiento
        print(f"{nombre} cumplirá {edad} años.")

calcular_edades()

![image](https://github.com/user-attachments/assets/9b209cd0-5c3d-4a1c-85c5-f64778071884)
![image](https://github.com/user-attachments/assets/7108c0e4-9e0b-465a-b192-964ec6e54f2b)

# PROGRAMA 7:
def contar_mayores(edades):
    return sum(1 for edad in edades if edad > 20)

# Ejemplo con tupla
edades = (15, 22, 18, 30, 45, 19, 25, 32, 10, 27)
print("Cantidad de mayores de 20:", contar_mayores(edades))

![image](https://github.com/user-attachments/assets/3c4dd25f-0c36-44c7-b755-0ff46517805a)
![image](https://github.com/user-attachments/assets/b89d8e67-212e-4827-a4c1-a5c6622a54df)

# PROGRAMA 8:
def contar_por_letra(nombres, letra):
    return sum(1 for nombre in nombres if nombre.lower().startswith(letra.lower()))

# Ejemplo
nombres = ["Ana", "Carlos", "andrea", "Juan", "Arturo"]
letra = input("Ingresa la letra a buscar: ")
print(f"Nombres que comienzan con '{letra}':", contar_por_letra(nombres, letra))


![image](https://github.com/user-attachments/assets/f07436d5-6a39-4f09-9da3-f0c9b0bfb34c)
![image](https://github.com/user-attachments/assets/19b8ee92-cc08-4ee8-99b6-0043cb6c4e48)

# PROGRAMA 9:
def contar_vocales(palabra):
    vocales = "aeiou"
    return {v: palabra.lower().count(v) for v in vocales}

# Ejemplo
palabra = input("Ingresa una palabra: ")
print(contar_vocales(palabra))

![image](https://github.com/user-attachments/assets/14f560ba-d66a-49ab-8b33-2ef642e8de3b)
![image](https://github.com/user-attachments/assets/969d248b-d7bb-491a-ad01-8e246de18701)

# PRORGRAMA 10:
def es_bisiesto(año):
    return (año % 4 == 0 and año % 100 != 0) or (año % 400 == 0)

# Ejemplo
año = int(input("Ingresa un año: "))
if es_bisiesto(año):
    print(f"{año} es un año bisiesto.")
else:
    print(f"{año} no es un año bisiesto.")

![image](https://github.com/user-attachments/assets/c14b0e8b-c124-4387-8a5b-107ae12add94)
![image](https://github.com/user-attachments/assets/7336ceeb-6ebd-41d7-8a80-5ed5f9658ba3)
