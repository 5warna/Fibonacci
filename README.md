#Fibonacci Series upto 10 terms
a = 0
b = 1
print("Fibonacci sequence: ")
for i in range(10):
    print(a, end =" ")
    sum = a + b
    a = b
    b = sum
    
