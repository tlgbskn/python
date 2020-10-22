##SAYI TAHMİN OYUNU

import random as rnd
secret = rnd.randint(1,100)
check = False
for x in range(5):
    guess = int(input("sayı tahmini girin:"))
    if guess == secret:
        print("tebrikler")
        check = True
        break
    elif guess < secret:
        print("daha büyük sayı girin")
    else:
        print("daha küçük değer girin")
if not check:
    print("yazık kaybettin", secret)
