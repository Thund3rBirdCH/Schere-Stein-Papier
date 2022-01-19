#!/bin/python3

from random import randint

spieler = input('Schere (s), Stein (r) oder Papier (p)?')


if(spieler == 's'):
  print('>8', end=' ')
  
if(spieler == 'r'):
  print('O', end=' ')
  
if(spieler == 'p'):
  print('_____', end=' ')

print('vs', end=' ') #vs ist hier nur für Versus = gegen


#Zufallsgenerator

zufall = randint(1,3)
#print(computer)

#Stein

if(zufall == 1):
  computer = 'r'
  print('O')
  
#Papier
  
elif(zufall == 2):
  computer = 'p'
  print('_____')
  
#Schere
  
else:
  computer = 's'
  print('>8')
  
#Ergebnisse
  
if(spieler == computer):
  print('Unentschieden!')
  
elif(spieler == 'r' and computer == 's'):
  print('Spieler gewinnt!')

elif(spieler == 'r' and computer == 'p'):
  print('Computer gewinnt!')
  
elif(spieler == 'p' and computer == 'r'):
  print('Spieler gewinnt!')

elif(spieler == 'p' and computer == 's'):
  print('Computer gewinnt!')

elif(spieler == 's' and computer == 'p'):
  print('Spieler gewinnt!')

elif(spieler == 's' and computer == 'r'):
  print('Computer gewinnt!')
