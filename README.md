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

