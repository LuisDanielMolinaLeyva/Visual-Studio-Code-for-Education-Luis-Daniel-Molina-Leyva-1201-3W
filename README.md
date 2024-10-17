# Visual-Studio-Code-for-Education-Luis-Daniel-Molina-Leyva-1201-3W

#Actividad

#Presentacion
print("Visual Studio Code for Education-Luis Daniel Molina Leyva 1201 3W")

print(" ")

#Permite escribir
x = input("Introducir tu Nombre: ")
y = input("Introducir tu Edad: ")
z = input("Introducir tu Genero: ")
w = input("Introducir tu Numero de telefono: ")
a = input("Introducir tu Correo electrónico: ")

print(" ")

#Muestra lo escrito
thisdict = {
'Nombre':x,
'Edad':y, 
'Genero':z,
'Telefono':w,
'Correo electrónico':a
}
print(thisdict)

![image](https://github.com/user-attachments/assets/23cf0b0d-6007-4e73-a1b5-98b48c5fddb8)
![image](https://github.com/user-attachments/assets/82a1401e-8fe5-4703-ae55-08b4a4b70954)

#Activida2

# Diccionario de traducción español-inglés predefinido
diccionario = {
    'hola': 'hello',
    'adiós': 'goodbye',
    'gracias': 'thank you',
    'por favor': 'please',
    'buenos días': 'good morning',
    'buenas noches': 'good night',
    'cómo estás': 'how are you',
    'bien': 'well',
    'mal': 'bad',
    'sí': 'yes',
    'no': 'no',
}

# Traducir una frase usando el diccionario
def traducir_frase(diccionario, frase):
    palabras = frase.split()
    traduccion = []
    for palabra in palabras:
        traduccion.append(diccionario.get(palabra, palabra))  # Mantiene la palabra sin traducir si no está en el diccionario
    return ' '.join(traduccion)

# Bucle para traducir frases
print("¡Bienvenido al traductor! Escribe 'salir' para terminar.")
while True:
    frase = input("\nIntroduce una frase en español para traducir: ")
    if frase.lower() == 'salir':
        print("¡Hasta luego! Gracias por usar el traductor.")
        break
    traduccion = traducir_frase(diccionario, frase)
    print("Traducción:", traduccion)

![image](https://github.com/user-attachments/assets/38f26a3f-7583-4f1d-9a60-1763aaaf201c)
![image](https://github.com/user-attachments/assets/a8046901-fc52-4cca-9590-277103600de9)

