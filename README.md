# currency-converter
print("converting one currency to another")
print("select from below currency")

print(" ")

print("Indian Rupee(INR)")
print(" United States Dollar(USD)")
print("Euro(EUR)")
print("Canadian Dollar(CAD)")
print("Chinese Yuan(CNY)")
print("Russian Ruble(RUB)")
print("Pakistani Rupee(PKR}")
print("United Arab Emirates Drihan(AED)")

print(" ")

From=input("currency that should be converted from: ")
To=input("currency that should be converted into: ")
print(" ")
a=float(input("Enter the amount: "))

if From=="INR" or From=="USD" or From=="EUR" or From=="CAD" or From=="CNY" or From=="RUB" or From=="PKR" or From=="AED" and To=="INR" or To=="USD" or To=="EUR" or To=="CAD" or To=="CNY" or To=="RUB" or To=="PKR" or To=="AED":
    if From=="INR" and To=="INR":
        print(a*1)
    elif From=="INR" and To=="USD":
        print(a*0.012)
    elif From=="INR" and To=="EUR":
        print(a*0.012)
    elif From=="INR" and To=="CAD":
        print(a*0.016)
    elif From=="INR" and To=="CNY":
        print(a*0.088)
    elif From=="INR" and To=="RUB":
        print(a*0.74)
    elif From=="INR" and To=="PKR":
        print(a*2.74)
    elif From=="INR" and To=="AED":
        print(a*0.045)
            
    elif From=="USD" and To=="INR":
        print(a*81.67)
    elif From=="USD" and To=="USD":
        print(a*1)
    elif From=="USD" and To=="EUR":
        print(a*0.96)
    elif From=="USD" and To=="CAD":
        print(a*1.34)
    elif From=="USD" and To=="CNY":
        print(a*7.17)
    elif From=="USD" and To=="RUB":
        print(a*60.50)
    elif From=="USD" and To=="PKR":
        print(a*223.50)
    elif From=="USD" and To=="AED":
        print(a*3.67)

    elif From=="EUR" and To=="INR":
        print(a*85.06)
    elif From=="EUR" and To=="USD":
        print(a*1.04)
    elif From=="EUR" and To=="EUR":
        print(a*1)
    elif From=="EUR" and To=="CAD":
        print(a*1.39)
    elif From=="EUR" and To=="CNY":
        print(a*7.47)
    elif From=="EUR" and To=="RUB":
        print(a*63.01)
    elif From=="EUR" and To=="PKR":
        print(a*232.76)
    elif From=="EUR" and To=="AED":
        print(a*3.83)

    elif From=="CAD" and To=="INR":
        print(a*60.94)
    elif From=="CAD" and To=="USD":
        print(a*0.75)
    elif From=="CAD" and To=="EUR":
        print(a*0.72)
    elif From=="CAD" and To=="CAD":
        print(a*1)
    elif From=="CAD" and To=="CNY":
        print(a*5.35)
    elif From=="CAD" and To=="RUB":
        print(a*45.14)
    elif From=="CAD" and To=="PKR":
        print(a*166.77)
    elif From=="CAD" and To=="AED":
        print(a*2.74)

    elif From=="CNY" and To=="INR":
        print(a*11.38)
    elif From=="CNY" and To=="USD":
        print(a*0.14)
    elif From=="CNY" and To=="EUR":
        print(a*0.13)
    elif From=="CNY" and To=="CAD":
        print(a*0.19)
    elif From=="CNY" and To=="CNY":
        print(a*1)
    elif From=="CNY" and To=="RUB":
        print(a*8.50)
    elif From=="CNY" and To=="PKR":
        print(a*31.15)
    elif From=="CNY" and To=="AED":
        print(a*0.51)

    elif From=="RUB" and To=="INR":
        print(a*1.35)
    elif From=="RUB" and To=="USD":
        print(a*0.017)
    elif From=="RUB" and To=="EUR":
        print(a*0.016)
    elif From=="RUB" and To=="CAD":
        print(a*0.022)
    elif From=="RUB" and To=="CNY":
        print(a*0.12)
    elif From=="RUB" and To=="RUB":
        print(a*1)
    elif From=="RUB" and To=="PKR":
        print(a*3.69)
    elif From=="RUB" and To=="AED":
        print(a*0.061)

    elif From=="PKR" and To=="INR":
        print(a*0.36)
    elif From=="PKR" and To=="USD":
        print(a*0.0045)
    elif From=="PKR" and To=="EUR":
        print(a*0.0043)
    elif From=="PKR" and To=="CAD":
        print(a*0.0060)
    elif From=="PKR" and To=="CNY":
        print(a*0.032)
    elif From=="PKR" and To=="RUB":
        print(a*0.27)
    elif From=="PKR" and To=="PKR":
        print(a*1)
    elif From=="PKR" and To=="AED":
        print(a*0.016)

    elif From=="AED" and To=="INR":
        print(a*22.24)
    elif From=="AED" and To=="USD":
        print(a*0.27)
    elif From=="AED" and To=="EUR":
        print(a*0.26)
    elif From=="AED" and To=="CAD":
        print(a*0.36)
    elif From=="AED" and To=="CNY":
        print(a*1.95)
    elif From=="AED" and To=="RUB":
        print(a*16.47)
    elif From=="AED" and To=="PKR":
        print(a*60.85)
    elif From=="AED" and To=="AED":
        print(a*1)
    else:
        print("pls mention the correct currency")
else:
    print("pls mention the correct currency")


