# AP---Arithmetic-Progression
This program show the 10 terms of a arithmetic progression. 


print(36 * '=')
print('10 TERMS OF A ARITHMETIC PROGRESSION')
print(36 * '=')

firstterm = int(input('Type the first term: '))
reason = int(input('Type the reason: '))
term = firstterm
cont = 1

while cont <= 10:
    print('{} -> '.format(term), end='')
    cont += 1
    term += reason
print('END')
