# sum-of-given-no.py

number = int(input("Enter number: "))
total_sum = 0
step = 1
condition = True
while condition:
    
    while number:
        total_sum += number%10
        number //= 10
    
    print("Step-%d Sum: %d" %(step, total_sum))
    number = total_sum
    total_sum = 0
    step += 1
    condition = number > 9



output:
Enter number: 3
Step-1 Sum: 3

