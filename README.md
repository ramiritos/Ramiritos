# Intereses

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
# CuentaBancaria(monto,INTERES,tiempo)
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
# CuentaBancaria(monto,INTERES,tiempo)