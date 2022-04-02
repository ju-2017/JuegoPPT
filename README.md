# JuegoPPT


print("--------------------------------------------------------------")
print("El juego consiste en hbchjchsfbshfsfjhsfhjshjfhsfsf sf sfhj sf svh")
print("---------------------------------------------------------------")


def menu():
    opcion = int(input("inserta un numero valor >> "+
                        "1. Jugar\n"+
                        " 2. Salir\n"+
                        "Elija una opcion: \n"))
   

    
    
    





selc = ["piedra", "papel", "tijera", "lagarto", "spock" ]

while True:
    
    menu()
    
    if opcionMenu=="1":
		print ("Vamor a jugar")
		input("Has pulsado la opción 1...\npulsa una tecla para continuar")
	elif opcionMenu=="2":
		break
	else:
		print ("")
		input("No has pulsado ninguna opción correcta...\npulsa una tecla para continuar")
    
    
    
    
    
    
    user1 = input("Elije: Piedra, Papel, Tijera, Lagarto, Spock: ")
    if user1 not in selc:
        print("\nOpcion no valida")
        continue
    user2 = input("Elije: Piedra, Papel, Tijera, Lagarto, Spock: ")
    if user2 not in selc:
        print("\nOpcion no valida")
        continue
    elif user1 == user2:
        print("\nLos dos jugadores elijieron la misma opcion {user1}")
    elif user1 == "piedra" and user2 == "tijera":
        print("\nHaz ganado {user1} Haz perdido {user2}")
    elif user1 == "tijera" and user2 == "papel":
        print("\nHaz ganado {user1} Haz perdido {user2}")
    elif user1 == "papel" and user2 == "piedra":
        print("\nHaz ganado {user1} Haz perdido {user2}")
    else:
        print ("\nHas perdido {user1} Haz ganado {user2} ")
