https://github.com/psiinon/bodgeit.git

# Binary_Monster

#!/usr/bin/env python
#-*-coding: utf-8 -*-

sayi = int(raw_input("Decimal tabandaki sayiyi giriniz :"))
a = sayi

liste = []

while sayi > 0:
	secsayi = sayi % 2
	liste.append(secsayi)
	sayi /= 2

magic = 8 - len(liste)

for i in range(magic):
	liste.append(0)

string = ""

for i in liste[::-1]:
	string += str(i)

print a, "sayisinin ikilik tabandaki karşılığı : ", string















