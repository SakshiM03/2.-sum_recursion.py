# 2.-sum_recursion.py
def recursive_sum(n):
    # Base case
    if n == 0:
        return 0

    # Recursive case
    return n + recursive_sum(n - 1)


num = 5

result = recursive_sum(num)

print("Sum from 1 to", num, "is:", result)

Output:

Sum from 1 to 5 is: 15
