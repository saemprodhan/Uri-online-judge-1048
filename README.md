# Uri-online-judge-1048
Salary Increase
slary = float(input())
if 0<=slary<=400:
    increase = 0.15*slary
elif 400 < slary <= 800:
    increase = 0.12 * slary
elif 800 < slary <= 1200:
    increase = 0.1 * slary
elif 1200 < slary <= 2000:
    increase = 0.07 * slary
elif slary > 1200:
    increase = 0.04 * slary
print(f"Novo salario: {(increase)+slary:.2f}\nReajuste ganho: {slary-(slary-increase):.2f}\nEm percentual: {(increase/slary)*100:.0f} %")
