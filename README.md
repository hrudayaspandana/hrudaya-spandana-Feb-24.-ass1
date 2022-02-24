# hrudaya-spandana-Feb-24.-ass1
def primenum(n):
    for i in range(2,n):
        if n%i==0:
            return False
    return True
l=[]
n=int(input('enter n:'))
c=0
for i in range(n):
    x=int(input())
    if primenum(x):
        l.append(x)
        c=c+1
print(l)
print('count of prime numbers:',c)
