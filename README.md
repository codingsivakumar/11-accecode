'''write a program to print the sum and average of n natural numbers using while loop
input 10
output sum = 55
      avg =5.5'''
-----------------------------------------------------------------------------

n=int(input("enter the value n:"))
sum, avg=0, 0
i=1
while i<=n:
    sum=sum+i
    i+=1
print("sum:",sum) 
print("avg:",sum/n)
