def is_prime(x):
    if x<=1:
        return False
    if x==2:
        return True
    if x%2==0:
        return False
    divisor = 3
    while divisor*divisor<=x:
        if x%divisor==0:
            return False
        divisor+=2
    return True
x=int(input(""))
if is_prime(x):
    print(f"{x} prime")
else:
    print(f"{x} not prime")
