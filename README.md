# hw11.10.21

==========targil 6 page 15 :

x = int(input("please enter a number"))
i = 1
digit = 0

while i < 3:
    digit = x % 10
    x = x // 10
    i += 1

print(digit)

==========targil 7 page 15 :

x = int(input("please enter a number"))
i = 1

while i < 3:
    x = x // 10
    i += 1

print(x)

==========targil 8 page 15 :

x = int(input("please enter a number"))
sum = (x//10) + (x%10)
print(sum)

==========targil 9 page 15

x = int(input("please enter a number"))

print( (x%10)*10 + (x//10) )


==========targil 10 page 15

x = float(input("please enter a number"))
y = int(x)

if y % 2 == 0:
    y = y + 2

else:
    y = y + 1

print(y)

==========targil 4 page 18

x = int(input("please enter a number"))
digit = 1

while x > 9:
    digit += 1
    x = x // 10

print(digit)

==========targil 5 page 18

sal = int(input("please enter a number"))
name = input("enter please a name")

if sal < 23000:
    tax = sal*0.1
elif sal < 46000:
    tax = (sal-23000)*0.2 + 2300
elif sal < 74000:
    tax = (sal-46000)*0.3 + 2300 + 4400
elif sal < 100000:
    tax = (sal- 74000)*0.4 + 2300 + 4400 + 8100
else:
    tax = (sal-100000)*0.5 + 8100 + 4400 + 2300 + 10400

print(name, "pays ", tax, "taxes")

==========targil 2 page 20

grade = int(input("please enter a number"))

if grade < 55:
    print("not enough")
elif grade < 65:
    print("enough")
elif grade < 75:
    print("almost good")
elif grade < 85:
    print("good")
elif grade < 95:
    print("very good")
else:
    print("exellent")
    
==========targil 13 page 25

x = int(input("please enter a number"))
dig = int(input("please enter a number"))
quantity = 0

if x < 0:
    x = x * (-1)

while x > 0:
    if x % 10 == dig:
        quantity +=1
    x = x // 10

print(quantity)
 
==========targil 14 page 25

x = int(input("please enter a number"))
dig = 0
opposite = 0

if x < 0:
    x = x * (-1)

while x > 0:
    dig = x % 10
    opposite = opposite*10 + dig
    x = x // 10

print(opposite)

==========targil 15 page 25

x = int(input("please enter a number"))
opposite = 0

if x < 0:
    x = x * (-1)
    
***targil 8 page 25:
  
x = int(input("please enter a number"))
min = x

while x > 0:

    if x < min:
        min = x

    x = int(input("please enter a number"))

if min > 0:
    print(min)
    
    
****targil 9 page 25

x = int(input("please enter a number"))

max = x
i = 1
counter = i

while i < 100:
    x = int(input("please enter a number"))
    i = i + 1
    if x > max:
        max = x
        counter = i

print(counter)
    

y = x

while x > 0:
    if x > 9:
           dig = x % 10
           opposite = opposite*10 + dig
    else:
        opposite = opposite*10 + x
    x = x // 10

if y == opposite:
    print("palindrome")
else:
    print("not palindrome")
    
=========targil 16 page 26

x = int(input("please enter a number"))
y = int(input("please enter a number"))
result = 0

i = 1

while i <= y:
    result = result + x
    i = i + 1

print(result)

=========targil 19 page 23

x = int(input('please enter the factorial request'))
atz = 1
i = 2
while i <= x:
    atz *= i
    i += 1
print(atz)

=========targil 23 page 26

x = int(input("please enter a number"))
i = 1

while i <= x:
    if x % i == 0:
        print(i)
    i += 1
    
=========targil 5 page 29

while True:
    x = int(input('enter a number for prime detection'))
    i = 2

    while x % i != 0:
        i += 1
    if i == x:
        break
    else:
        print(x)
