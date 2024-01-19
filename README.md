#BanoQabil2.0
def C_To_F():
    c=float(input("Input temperature in celsius:"))
    F=((c*1.8)+32)
    print("Temperature in fahrenheit is","%.2f"%F,"°F")



def F_To_C():
    f=float(input("Input temperature in fahrenheit:"))
    C=((f-32)/1.8)
    print("Temperature in celsius is","%.2f"%F,"°C")

def main():
    print('''
             A.Convert Temperature Celsius To Fahrenheit
             B.Convert Temperature Celsius To Fahrenheit''')
    X=input("Enter Your Choice..?")
    if (X=='A'):
        C_To_F()

    elif (X=='B'):
        F_To_C()

    else:
        print("Wrong Choice..!")
main()
