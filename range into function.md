On line 8, replace the ____ with a range() that returns a list containing [0, 1, 2].

def myFun(x):
for i in range(0,len(x)):
x[i] = x[i] * 2
print x[i]
return x
print myFun(range(0,1,2))

##sol

def my_function(x):
    for i in range(0, len(x)):
        x[i] = x[i] * 2
    return x

print my_function(range(0,3,1)) # Add your range between the parentheses
