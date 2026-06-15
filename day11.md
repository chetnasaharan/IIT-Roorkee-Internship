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
