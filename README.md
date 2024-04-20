# amount-discount-calculations
amo=int(input("Enter the amount : "))
if amo>=10000:
    dict=amo*20/100
    print("Amount to be paied after discount: ",amo-dict)
elif amo>=5000 and amo<10000:
    dict=amo*10/100
    print("Amount to be paied after discount: ",amo-dict)
elif amo>=1000 and amo<5000:
    dict=amo*5/100
    print("Amount to be paied after discount: ",amo-dict)
else:
    print("No discount amount to be paied: ",amo)
