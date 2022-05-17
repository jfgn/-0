Программа 1

print("София")
print(«Sofiya.fed@mail.ru»)

Программа 2

name = input("Введите имя: ")
print("Здравствуйте,", name)

Программа 3

a= float(input(«Введите длину комнаты:»))
b= float(input(«Введите ширину комнаты:»))
print(«Площадь комнаты= », a*b)

Программа 5

a= int(input("Введите количество бутылок 1л: "))
b= int(input("Введите кольчество бутылок >1л: "))
print("%.2f" % (a*0.1+b*0.25), "$")

Програма 6

summ= int(input("Какая сумма заказа? "))
ch=summ*0.18
nal=summ*0.13
itog=summ+ch+nal
print("Налог ","%.2f" % (nal), "$")
print("Чаевые ","%.2f" % (ch), "$")
print("Итог ","%.2f" % (itog), "$")

Программа 7

s= int(input("Введите число "))
for i in range (1, s):
 summ=i*(i+1)/2
print("summ= ","%.2f" % (summ))

Программа 8

s= int(input("Введите количество сувениров "))
b= int(input("Введите количество безделушек "))
h=s*75+b*112
print("Вес= ","%.2f" % (h))

Программа 9

s= int(input("Введите размер депозита "))
summ=s
for i in range (1, 4):
 summ=summ+summ*0.04
 print("Cумма на счету в конце ",i, " года= ", "%.2f" % (summ))

Программа 10

import math
a= int(input("Введите число a "))
b= int(input("Введите число b "))
z=math.log10(a)
print("сумма a и b=" , (a+b))
print("разница между a и b=" , (a-b))
print("произведение a и b=" , (a*b))
print("частное от деления a на b=" , (a/b))
print("остаток от деления a на b=" , (a%b))
print("десятичный логарифм числа a=" , z)
print("результат возведения числа a в степень b=" , (a**b))


Программа 11

import math
r= int(input("Введите радиус "))
p=math.pi
print("Площадь круга=" , (p*r*r))
print("объём шара=" , (1/3*p*r*r*r))

Программа 12

import math
r= int(input("Введите радиус "))
h= int(input("Введите высоту "))
p=math.pi
print("объём цилиндра=" , (p*r*r*h))

Программа 13

import math
h= int(input("Введите высоту "))
g=9.8 
v1=0
print("Cкорость при соприкосновении объекта с землей=" , (math.sqrt(2*g*h)))
