
#Ingresar una secuencia de tuplas y luego consultar si una tupla existe en el conjunto de datos.

import os 
import sys

u=input()

fr=u.split(",")

#Conocemos la cantidad de tuplas que ingresara el usuario

m=int(fr[0])

#Cantidad de tuplas a buscar

n=int(fr[1])

lista = []

if m>0 and n>0:
    o=n+m
    for e in range(o):
        m=input().split(",")
        lista.append(m)    
    q=lista[:len(lista)-n]
    buscamos=lista[len(lista)-n:]
    ;










