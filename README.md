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

