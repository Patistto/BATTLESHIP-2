# Tablero de juego con tamaño 6x8
tablero_jugador1 = [
    [' ', '1', '2', '3', '4', '5', '6'],
    ['A', '■', '■', '■', '■', '■', '■'],
    ['B', '■', '■', '■', '■', '■', '■'],
    ['C', '■', '■', '■', '■', '■', '■'],
    ['D', '■', '■', '■', '■', '■', '■'],
    ['E', '■', '■', '■', '■', '■', '■'],
    ['F', '■', '■', '■', '■', '■', '■'],
    ['G', '■', '■', '■', '■', '■', '■'],
    ['H', '■', '■', '■', '■', '■', '■']
]

tablero_jugador2 = [
    [' ', '1', '2', '3', '4', '5', '6'],
    ['A', '■', '■', '■', '■', '■', '■'],
    ['B', '■', '■', '■', '■', '■', '■'],
    ['C', '■', '■', '■', '■', '■', '■'],
    ['D', '■', '■', '■', '■', '■', '■'],
    ['E', '■', '■', '■', '■', '■', '■'],
    ['F', '■', '■', '■', '■', '■', '■'],
    ['G', '■', '■', '■', '■', '■', '■'],
    ['H', '■', '■', '■', '■', '■', '■']
]

# Barcos del jugador 1
barcos_jugador1 = [
    {'fila': 'A', 'columna': 1, 'tamaño': 2, 'orientacion': 'v'},  # Barco vertical de 2 casillas en A6-B6
    {'fila': 'D', 'columna': 3, 'tamaño': 2, 'orientacion': 'h'},  # Barco horizontal de 2 casillas en D3-D4
    {'fila': 'H', 'columna': 5, 'tamaño': 2, 'orientacion': 'h'},  # Barco horizontal de 2 casillas en H5-H6
    {'fila': 'F', 'columna': 1, 'tamaño': 1, 'orientacion': 's'},  # Barco solo en F1
    {'fila': 'H', 'columna': 3, 'tamaño': 1, 'orientacion': 's'},  # Barco solo en H3
    {'fila': 'B', 'columna': 3, 'tamaño': 1, 'orientacion': 's'}   # Barco solo en B3
]

# Barcos del jugador 2
barcos_jugador2 = [
    {'fila': 'A', 'columna': 1, 'tamaño': 2, 'orientacion': 'v'},  # Barco vertical de 2 casillas en A1-B1
    {'fila': 'E', 'columna': 1, 'tamaño': 2, 'orientacion': 'h'},  # Barco horizontal de 2 casillas en E1-E2
    {'fila': 'F', 'columna': 5, 'tamaño': 2, 'orientacion': 'h'},  # Barco horizontal de 2 casillas en F5-F6
    {'fila': 'G', 'columna': 2, 'tamaño': 1, 'orientacion': 's'},  # Barco solo en G2
    {'fila': 'A', 'columna': 4, 'tamaño': 1, 'orientacion': 's'},  # Barco solo en A4
    {'fila': 'D', 'columna': 6, 'tamaño': 1, 'orientacion': 's'}  # Barco solo en D6
]

# Ataques de cada jugador
ataques_jugador1 = []
ataques_jugador2 = []

# Cantidad de barcos ocultos en el tablero
barcos_ocultos = 6

# Cantidad de disparos que cada jugador tiene
disparos_jugador1 = 18
disparos_jugador2 = 18

while True:
    # Mostrar los tableros y ataques restantes
    print("Tablero de jugador 1:")
    for fila in tablero_jugador1:
        for c in fila:
            print(c, end=' ')
        print()
    print("Ataques restantes del jugador 1:", disparos_jugador1 - len(ataques_jugador1))
    print("Tablero de jugador 2:")
    for fila in tablero_jugador2:
        for c in fila:
            print(c, end=' ')
        print()
    print("Ataques restantes del jugador 2:", disparos_jugador2 - len(ataques_jugador2))

    # Ataque del jugador 1
    fila = input("Introduce la fila del ataque (A-H): ")
    fila_dict = {'A': 0, 'B': 1, 'C': 2, 'D': 3, 'E': 4, 'F': 5, 'G': 6, 'H': 7}
    fila = fila_dict[fila]
    columna = int(input("Introduce la columna del ataque (1-6): ")) - 1

    # Verificar si el ataque ya se ha realizado
    if (fila, columna) in ataques_jugador1:
        print("Este ataque ya se ha realizado.")
        continue

    # Verificar si el ataque está dentro de los límites del tablero
    if fila < 0 or fila > 7 or columna < 0 or columna > 5:
        print("Ataque fuera de los límites del tablero.")
        continue

    # Marcar el ataque como realizado
    ataques_jugador1.append((fila, columna))

    # Verificar si el ataque ha acertado a un barco
    hit = False
    for barco in barcos_jugador2:
        if barco['orientacion'] == 'h' and fila == barco['fila'] and columna >= barco['columna'] and columna < barco['columna'] + barco['tamaño']:
            hit = True
            # Marcar el barco como dañado
            barco['tamaño'] -= 1
            if barco['tamaño'] == 0:
                # Eliminar todas las casillas del barco
                for i in range(barco['columna'], barco['columna'] + barco['tamaño']):
                    tablero_jugador2[fila][i] = 'X'
                print("Has hundido un barco!")
                barcos_jugador2.remove(barco)
            else:
                tablero_jugador2[fila][columna] = 'X'
                print("¡BUENA! Has acertado a un barco.")
        elif barco['orientacion'] == 'v' and fila >= barco['fila'] and fila < barco['fila'] + barco['tamaño'] - 1 and columna == barco['columna']:
            hit = True
            # Marcar el barco como dañado
            barco['tamaño'] -= 1
            if barco['tamaño'] == 0:
                # Eliminar todas las casillas del barco
                for i in range(barco['fila'], barco['fila'] + barco['tamaño']):
                    tablero_jugador2[i][columna] = 'X'
                print("Has hundido un barco!")
                barcos_jugador2.remove(barco)
            else:
                tablero_jugador2[fila][columna] = 'X'
                print("¡BUENA! Has acertado a un barco.")
        elif barco['orientacion'] == 's' and fila == barco['fila'] and columna == barco['columna']:
            hit = True
            # Marcar el barco como dañado
            barco['tamaño'] -= 1
            if barco['tamaño'] == 0:
                tablero_jugador2[fila][columna] = 'X'
                print("Has hundido un barco!")
                barcos_jugador2.remove(barco)
            else:
                tablero_jugador2[fila][columna] = 'X'
                print("¡BUENA! Has acertado a un barco.")
    
    # Si no se ha acertado a un barco, marcar el ataque como fallido
    if not hit:
        tablero_jugador2[fila][columna] = 'M'
        print("¡MAL! No has acertado a ningún barco.")

    # Verificar si el jugador 1 ha ganado
    if len(barcos_jugador2) == 0:
        print("¡FELICIDADES! Has ganado el juego.")
        break

    # Ataque del jugador 2
    fila = input("Introduce la fila del ataque (A-H): ")
    fila_dict = {'A': 0, 'B': 1, 'C': 2, 'D': 3, 'E': 4, 'F': 5, 'G': 6, 'H': 7}
    fila = fila_dict[fila]
    columna = int(input("Introduce la columna del ataque (1-6): ")) - 1

    # Verificar si el ataque ya se ha realizado
    if (fila, columna) in ataques_jugador2:
        print("Este ataque ya se ha realizado.")
        continue

    # Verificar si el ataque está dentro de los límites del tablero
    if fila < 0 or fila > 7 or columna < 0 or columna > 5:
        print("Ataque fuera de los límites del tablero.")
        continue

    # Marcar el ataque como realizado
    ataques_jugador2.append((fila, columna))

    # Verificar si el ataque ha acertado a un barco
    hit = False
    for barco in barcos_jugador1:
        if barco['orientacion'] == 'h' and fila == barco['fila'] and columna >= barco['columna'] and columna < barco['columna'] + barco['tamaño']:
            hit = True
            # Marcar el barco como dañado
            barco['tamaño'] -= 1
            if barco['tamaño'] == 0:
                # Eliminar todas las casillas del barco
                for i in range(barco['columna'], barco['columna'] + barco['tamaño']):
                    tablero_jugador1[fila][i] = 'X'
                print("Has hundido un barco!")
                barcos_jugador1.remove(barco)
            else:
                tablero_jugador1[fila][columna] = 'X'
                print("¡BUENA! Has acertado a un barco.")
        elif barco['orientacion'] == 'v' and fila >= barco['fila'] and fila < barco['fila'] + barco['tamaño'] and columna == barco['columna']:
            hit = True
            # Marcar el barco como dañado
            barco['tamaño'] -= 1
            if barco['tamaño'] == 0:
                # Eliminar todas las casillas del barco
                for i in range(barco['fila'], barco['fila'] + barco['tamaño']):
                    tablero_jugador1[i][columna] = 'X'
                print("Has hundido un barco!")
                barcos_jugador1.remove(barco)
            else:
                tablero_jugador1[fila][columna] = 'X'
                print("¡BUENA! Has acertado a un barco.")
        elif barco['orientacion'] == 's' and fila == barco['fila'] and columna == barco['columna']:
            hit = True
            # Marcar el barco como dañado
            barco['tamaño'] -= 1
            if barco['tamaño'] == 0:
                tablero_jugador1[fila][columna] = 'X'
                print("Has hundido un barco!")
                barcos_jugador1.remove(barco)
            else:
                tablero_jugador1[fila][columna] = 'X'
                print("¡BUENA! Has acertado a un barco.")
    
    # Si no se ha acertado a un barco, marcar el ataque como fallido
    if not hit:
        tablero_jugador1[fila][columna] = 'M'
        print("¡MAL! No has acertado a ningún barco.")

    # Verificar si el jugador 2 ha ganado
    if len(barcos_jugador1) == 0:
        print("¡FELICIDADES! Has ganado el juego.")
        break

    # Decrementar disparos
    disparos_jugador1 -= 1
    disparos_jugador2 -= 1

    # Verificar si un jugador ha agotado sus ataques
    if disparos_jugador1 == 0:
        print("¡PERDISTE! No tienes más ataques.")
        break
    elif disparos_jugador2 == 0:
        print("¡PERDISTE! No tienes más ataques.")
        break

