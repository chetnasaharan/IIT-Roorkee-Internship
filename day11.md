DAY 1

name = input('enter your name :')
age = input('enter your age :')
print(f'Hello, {name}! I am surprised to see you are only {age}')
print('Hello,',name,"! I am surprised to see you are only", age )
print('Hello, '+name+"! I am surprised to see you are only "+ age )
Hello, Bhupesh! I am surprised to see you are only 22
Hello, Bhupesh ! I am surprised to see you are only 22
Hello, Bhupesh! I am surprised to see you are only 22
a = 42
b = 3.14159
c = 'mathematics'
d = True
print('a is :', type(a))
print('b is :', type(b))
print('c is :', type(c))
print('d is :', type(d))
a is : <class 'int'>
b is : <class 'float'>
c is : <class 'str'>
d is : <class 'bool'>
a = input('enter first number')
b = input('enter second number')
num1 = float(a)
num2 = float(b)
print(f"addition : {num1+num2}")
print('addition : ', num1+num2)
print(f"subtraction : {num1-num2}")
print(f"multipication : {num1*num2}")
print(f"division : {num1/num2}")
addition : 10.0
addition :  10.0
subtraction : -2.0
multipication : 24.0
division : 0.6666666666666666

Practice sheet 1


a = input('enter weight in kgs : ')
b = input('enter height in meters: ')
wt = float(a)
ht = float(b)
bmi = wt/ht**2
print(f'your BMI is {bmi}')
if bmi >= 25.0:
    print('result : overweight')
elif bmi < 18.5 :
    print ('result : underweight')
else :
    print('result: normal')
your BMI is 24.163265306122447
result: normal
print('choose a conversion') 
print('1.Celsius to Fahrenheit')
print('2.Fahrenheit to Celsius')
choice = input('Enter 1 or 2: ')
if choice == '1':
     C = float(input('enter temperature in Celsius: '))
     F = (9*C/5) + 32
     print(f"{C:.2f} celsius is {F:.2f} Fahrenheit.")
elif choice == '2': 
     F = float(input('Enter temperature in Fahrenheit: '))
     C = (F-32)*5/9
     print (f"{F:.2f} fahrenheit is {C:.2f} celsius.")
else:
     print("Choose a valid conversion")
     
 
choose a conversion
1.Celsius to Fahrenheit
2.Fahrenheit to Celsius
37.70 celsius is 99.86 Fahrenheit.
#simple interest code 
P = float(input('Enter principal amount: '))
R = float(input('Enter the rate of interest per annum(in %): '))
T = float(input('Enter the time (in years)'))
si = (P*R*T)/100
print(f"The simple interest for given data is : {si}.")
The simple interest for given data is : 120.0.
