# PythonProg
s=input("enter input")
res=[s[i:j +1] for i in range(len(s)) for j in range(i,len(s))]
v=['a','e','i','o','u']
count=0
for char in res:
    if char in v:
        count=count+1
print(count)
