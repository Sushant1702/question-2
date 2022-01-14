# question-2
standard_deduction = 10000
gross_income = float(input("Gross income is :"))
count_of_dependent = int(input("Number of dependents are :"))
dependent_deduction = 3000*int(count_of_dependent)
taxable_income = float(gross_income) - standard_deduction - dependent_deduction
print("Taxable income is :",taxable_income)
tax = int(taxable_income)*0.2
print("Total taxable income is :",tax)
