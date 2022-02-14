# assignment1-14-02-22
find number of digits in a given number
n=int(input("Enter number:"))
count=0
while(n>0):
    count=count+1
    n=n//10
print("The number of digits in the number are:",count)
Enter number:65432
The number of digits in the number are: 5
