# Test2
Testing
print('Введите коэфиценты квадратного уравнения')
a = int(input())
b = int(input())
c = int(input())
if b == 0:
    vrem_ab = a/(-c)
    if vrem_ab > 0:
        print('+-', vrem_ab**0.5)
    else:
        print('No roots')
if a == 0:
    print
