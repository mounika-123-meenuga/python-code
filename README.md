# python 

[Python_assginment - Copy.pdf](https://github.com/mounika-123-meenuga/python-code/files/9643624/Python_assginment.-.Copy.pdf)
# output
for _ in range(int(input())):
    n, k = map(int, input().split())
    arr = list(map(int, input().split()))
    print(sum(x > k for x in arr))
