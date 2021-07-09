# 21_Days_Utkarsh_Dubey
Utkarsh 
KJSCE

Beginner

Day 1: Basic Concept
x = input("Enter the value of item 1: ")
y = input("Enter the value of item 2: ")

add = int(x) + int(y)

tax = add*0.1

total = add + tax

if total >= 1000:
    total = total - total*0.1
elif total <= 1000 and total >=500:
    total = total = total*0.07
else: 
    pass

print(total)

Day 2: Loops
