# Fibonacci_series-
N = int(input("how many Terms? = "))
n1 = 0
n2 = 1
count = 0
if N <= 0:
    print("enter a valid +ve Integer ")
elif N == 1:
    print("Fibonacci Sequence upto",N,":")
    print(n1)
else:
    print("Fibonacci sequence:")
    while count < N:
        print(n1)
        nth = n1 + n2
        n1 = n2
        n2 = nth
        count += 1
