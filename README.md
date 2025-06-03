# pyhton_fundamentals
#CHECK THE PRIME NUMBER OR NOT
n = 17  # Change this value to check other numbers

if n < 2:
    print(f"{n} is not a prime number")
else:
    count = 0
    for i in range(1, n + 1):
        if n % i == 0:
            count += 1
    if count == 2:
        print(f"{n} is a prime number")
    else:
        print(f"{n} is not a prime number")
