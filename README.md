# homework_3_if...
print("hello")

Gross = int(input("Enter Gross salary"))
if Gross > 4000:
    income_tax = 0.18
elif Gross > 2000 and Gross <=4000:
    income_tax = 0.14
elif Gross > 1000 and Gross <=2000:
    income_tax = 0.12
else:
    income_tax = 0.1
Children = int(input("Enter number of children"))
if Gross < 2000:
    cut_tax = income_tax - (Children*0.01)
else:
    cut_tax = income_tax - (Children*0.005)
Net = Gross - (Gross*cut_tax)
print ("Net salary is", Net)
