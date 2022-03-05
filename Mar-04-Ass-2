#program to print second runner up in the given list
l=[]
n=int(input('enter no.of elements: '))
for i in range(n):
    x=int(input())
    l.append(x)
l.sort(reverse=True)
print(l)
res=[]
for i in l:
    if i not in res:
        res.append(i)
k=len(res)
if k>3:
    print(res[2])
else:
    print(res[k-1])
