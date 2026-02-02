# Python-program-to-generate-the-prime-numbers-from-1-to-N
num =int(input("Enter the range: "))
for n in range(1,num):
    for i in range(2,n):
        if(n%i==0):
            break
    else:
        print(n)   
output:
Enter the range: 5
1
2
3
