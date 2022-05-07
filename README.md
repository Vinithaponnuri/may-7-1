n=int(input())
l=[]
d={}
for i in range(n):
  x=int(input())
  l.append(x)
j=1
for i in l:
  if i%2==0:
    print('yes',end='')
  else:
    print('no',end='')
 x=int(input())
 print(d.get(x))
