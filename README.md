# simple-calculator-
# Very basic and easy way to bulid a simple calculation of two numbers simultaneously. 
calculation= input('''FOR ADDITION PRESS : + ,FOR SUBSTRACT PRESS : - ,FOR DIVISION PRESS : /  ,FOR MULPICATION PRESS : * ,FOR MODULES PRESS : %
PRESS HERE  :::''')

x=float(input("ENTER YOUR FIRST NUMBER : " ))
y=float(input("ENTER YOUR SECOND  NUMBER : " ))
if calculation=='+':
    print("ADDITION OF TWO NUMBERS IS :",x+y)
elif calculation=='*':
    print("MULTIPLICATION OF TWO NUMBERS IS :",x*y)
elif calculation=='%':
    print("MODULUS OF TWO NUMBERS IS :",x%y)
elif calculation=='-':
    print("SUBTRACTION OF TWO NUMBERS IS :",x-y)
elif calculation=='/':
    print("DIVISION OF TWO NUMBERS IS :",x/y)
else:
    print('PLEASE CHECK !')
    print ("ENTER VALID INPUT")
    
