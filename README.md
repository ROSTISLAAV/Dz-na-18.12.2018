1)
import random
a , vid , dod , nul = [] , 0 , 0 , 0
for i in range (20):
    a.append(int(random.uniform(-5,4)))
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
