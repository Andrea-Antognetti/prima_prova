#Codice scritto l'altro giorno in python

def estimate_prob_k_people(k,n):
  return sum([k > len(set([floor(random()*365) for _ in range(k)])) for _ in range(n)])/n

#sto modificando il file del branch secondario

modifica 1
