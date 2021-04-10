# Faulty-calculator
# exercise: misson faulty calculator.

num1 = int(input("Input your first number-"))
num2 = int(input("Input your second number-"))
sym  = str(input("Select a sybol['+','-','*','/']-"))


if num1 == 11 and num2 == 5 and sym == '*' :
    print("99")

elif num1 == 20 and num2 == 15 and sym == '/' :
    print("3")

elif num1 == 80 and num2 == 20 and sym == '+' :
    print("300")

elif '+':
    plus = num1 + num2
    print(plus)

elif '-':
    min = num2 - num1
    print(min)

elif '*':
    mul = num1 * num2
    print(mul)

elif '/':
    dev = num2 / num1
    print(dev)

else :
    print("Error!!!")

#MD.NAHIAN AHMED.
