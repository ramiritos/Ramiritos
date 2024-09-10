# EJERCICIO 1

`
## Leer tres números
num1 = int(input("Introduce el primer número: "))
num2 = int(input("Introduce el segundo número: "))
num3 = int(input("Introduce el tercer número: "))

## Ordenar los números ascendentemente
numeros = [num1, num2, num3]
numeros.sort()

## Imprimir los números ordenados
print("Números en orden ascendente:", numeros)

`

# EJERCICIO 2 INTERESES

` 
monto=0
while monto<=0:
    monto=float(input("Ingrese el monto que desea ingresar a la cuenta: "))
    if(monto<=0):
        print("Error al ingresar el monto")
tiempo=0
while tiempo<=0:
    tiempo= int(input("Ingrese el tiempo en años: "))
    if(tiempo<=0):
        print("Error al ingresar al tiempo") 
INTERES=0.02

def CuentaBancaria(mon,inter,tiem):
    interes = mon * inter * tiem
    return interes

resultado = CuentaBancaria(monto,INTERES,tiempo)
print(f"El interes sería: {resultado}")
`

# EJERCIO 3 NUMERICAS LITERRALES

`
numeros_a_texto = ['cero', 'uno', 'dos', 'tres', 'cuatro', 'cinco', 'seis', 'siete', 'ocho', 'nueve',
                   'diez', 'once', 'doce', 'trece', 'catorce', 'quince', 'dieciséis',
                   'diecisiete', 'dieciocho', 'diecinueve', 'veinte']

def numero_a_texto(n):
    if 0 <= n <= 20:
        return numeros_a_texto[n]
    else:
        return "Número fuera de rango"

def promediar_notas(nota1, nota2):
    return round((nota1 + nota2) / 2)

nota1 = int(input("Ingresa la primera nota (0-20): "))
nota2 = int(input("Ingresa la segunda nota (0-20): "))

promedio = promediar_notas(nota1, nota2)

promedio_texto = numero_a_texto(promedio)

print(f'El promedio de las dos notas es: {promedio} -> {promedio_texto}')

`

# EJERCICIO 4 SEXAGESIMAL

`
    import math 

def ConvertiraRadianes(grado_sexa):
    rad = float((grado_sexa * math.pi)/180)
    return rad

def ConvertiraSexadeciamles(radian):
    sexade = float((radian *180)/math.pi)
    return sexade

print("Que desa convertir?")
respuesta = input("1. Convertir sexagesimales\n2. Convertir a radianes")

if respuesta == 1:
    radianes = input("Ingresa la cantidad en radianes: ")
    resultado = ConvertiraSexadeciamles(radianes)
    print(f"La cantidad en grados sexagesimales es: "+resultado)
else:
    sexagesiamles = input("Ingresa los grados sexagesimales")
    resultado = ConvertiraRadianes(sexagesiamles)
    print(f"La cantidad en radianes es: "+resultado)

`

# EJERCICIO 5 CUADRADO
