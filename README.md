1)
import random
a , vid , dod , nul = [] , 0 , 0 , 0
for i in range (20):
    a.append(int(random.uniform(-5,5)))
    if a[i]<0:
        vid+=1
    elif a[i]==0:
        nul+=1
    else:
        dod+=1
print(a)
print('відємні:',vid)
print('нуль:',nul)
print('додотні:',dod)


2)
import random
a , vid  , dod , b = [] , [] , [], int(input('кількість чисел'))
for i in range (b):
    a.append(int(random.uniform(-5,5)))
    if a[i]<0:
        vid.append(a[i])
    elif a[i]>0:
        dod.append(a[i])
print(a)
print('відємні:',vid)
print('додотні:',dod)


3)
a = [int(i) for i in input().split()]
max , c = 0 , 0
for i in range(len(a)):
    c=int(a[i])
    c=abs(c)
    if c>max:
        max=c
print(max)


4)
x1=int(input())
y1=int(input())
x2=int(input())
y2=int(input())
if abs(x1 - x2) == abs(y1 -y2):
    print('YES')
else:
    print('NO')
