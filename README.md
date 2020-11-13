# day-2
ANS 1.
l=[]
for i in range(10):
    i=input(" Please enter a even number: ")
    l.append(i)
print(l)

ANS 2.
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = []

for x in fruits:
  if "i" in x:
    newlist.append(x)

2.1
print(newlist)

fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = [x for x in fruits if "k" in x]

print(newlist)

Ans3.
n=int(input("Input a number "))
d = dict()

for i in range(1,n+1):
    d[i]=i*i

print(d)
