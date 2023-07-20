# Sets-Filtro-de-funcion-rios
Programa em Python utilizando sets para filtrar funcionários!
listfuncionarios=['Ana','Marcos','Alice','Pedro','Sophia','Bruno','Melissa']
listturnodia=['Ana','Marcos','Alice','Melissa']
listturnoite=['Pedro','Sophia','Bruno']
listtemcarro=['Marcos','Alice','Bruno','Melissa']


num1 = set(listfuncionarios)
num2 = set(listturnodia)
num3 = set(listturnoite)
num4 = set(listtemcarro)

print(num3 & num4)
print(num2 & num4)
print(num1 - num4)
