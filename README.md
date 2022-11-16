from numpy import *
n=int(input("donner n : "))
while not(3<=n<=30):
    n=int(input("error(in faux 3<n<30) : "))
tab=[]
for i in range (0,n,1):
    t=int(input("number = "))
    while not (110<=t<=180):
        t=int(input("error (110<=t<=180) : "))
    t.append(tab)
print(tab)
