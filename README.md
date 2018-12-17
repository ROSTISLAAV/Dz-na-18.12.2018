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
