|№|Статус|
|------|------|
|0||
|1||
|2||
|3||
|4||
|5||
|6||
|7||
|8||
|9||
|10||
|11||
|12||
|13||
|14||
|15||
|16||
|17||
|18||
|19||
|20||
|21||
|22||
|23||
|24||
|25||
|26||
|27||


|||python
for i in range(1,100):
    chislo=''
    num=(bin(i)[2:])
    if num.count('1')%2==0:
        chislo='10'+num[2:]+'0'

    if num.count('1')%2!=0:
        chislo='11'+num[2:]+'1'
    if int(chislo,2)>40:
        print (i, int(chislo,2))
        break
|||

from turtle import *
left(90)
for i in range(7):
    forward(300)
    right(120)
pu()
for x in range(1,9):
    for y in range(1,10):
        goto(x*30,y*30)
        dot(5)
done()
