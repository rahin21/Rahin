a = input('Type the first number')
b = input('Type the second number')
c = input('Type the third number')

if a > b:
    if a > c:
        print(f"{a} is the greatest number")
    else:
        print(f"{c} is the greatest number")
else:
    if b > c:
        print(f"{b} is the greatest number")
    else:
        print(f"{c} is the greatest number")
