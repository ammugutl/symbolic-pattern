# symbolic-pattern
a=[]
for i in range(3):
  x=[]
  for j in range(3):
    x.append("*")
  a.append(x)
for i in a:
  print(*i,sep=" ")
