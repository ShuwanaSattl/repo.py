x = 1
y = 2.8
z = 1j

print(type(x))
print(type(y))
print(type(z))

x = -35e3
print(type(x))

a = float(x)
b = int(y)
c = complex(x)
print(a)
print(b)
print(c)
print(type(a))
print(type(b))
print(type(c))

import random 
print(random.randrange(1,10))
a =  '''Pakistan is very beautiful country, it has four province'''
print(a)
a = 200
b = 33
if b > a:
    print("b is greater than a")
else:
    print("b is not greater than a")    
x = "hello"
y = "15"
print(bool(x))
print(bool(y))
x = ["apple","cherry"]
y = ["apple"," cherry"]
z = x
print(x)
print(x)
print(x >=y)
print(x is not z)
print(x is not y)
print(x != y)
print("pineapple"not in x)
print((6+3)-(6-3))
mytuple = ("apple", "banana", "cherry")
print(type(mytuple))
x = {"a","b","c"}
y = (1,2,3)
z = x.union(y)
print(z)
thisdict = dict(name = "ayan", age = 15, country = "Pakistan")
print(thisdict)
x = frozenset(("apple","mango","cherry"))
print(x)
print(type(x))
