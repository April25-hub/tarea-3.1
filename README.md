# tarea-3.1
Arzaba Diaz April 1173 3W

print("Arzaba Diaz April")

print("3W")

print("1173")

#esta linea es el diccionario que relaciona las divisas con sus símbolos

divisas = {

    'euro': '€',
    
    'dollar': '$',
    
    'yen': '¥'
}




#esta linea solicitara al usuario que ingrese una divisa

entrada = input("introduce una divisa (euro, dollar, yen): ").strip().lower()



#esta linea verificara si la divisa ingresada está en el diccionario

if entrada in divisas:

    #esta linea mostrara el símbolo de la divisa
    
    print(f"el símbolo de {entrada.capitalize()} es: {divisas[entrada]}")
else
:

    #esta linea dara el mensaje si la divisa no está en el diccionario
    
    print("la divisa no está en el diccionario")
![image](https://github.com/user-attachments/assets/802f628d-976d-400d-adac-148f7cbc91f4)
![image](https://github.com/user-attachments/assets/1608c76a-3ffa-4d39-9e0c-3d1c140f4677)

