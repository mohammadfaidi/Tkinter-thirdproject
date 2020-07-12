# Tkinter-thirdproject


Now let’s create something from the real world, maybe a loan interest calculator. For that, we need a couple of items(variables) to be known, like principal amount, loan rate (r), balance (Bs) after s payments. To calculate loan after s payment, we use the formula in below program −

Ps = ((1+r)^s.Bo) – (((1 + r)^s – 1)/ r)*p
Where −

Rate = Rate of interest like 7.5%

i = rate/100, annual rate in decimal

r = period rate = i/12

Po = Principal amount

Ps = Balance after s payments

s = number of monthly payments

p = period (monthly) payment

So below is the Interest rate calculator program, which will show a pop-up window, where users can set desired value (loan amount, rate, number of installments) and will get the monthly payment amount and remaining loan he needs to pay with the help of python tkinter library.
