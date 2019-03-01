# python-basic-programs
Reverse of a number:
n=int(input("enter any number:")
rev=0
reminder=n%10
rev=(rev*10)+reminder
n=n//10
print("reverse of a number is=%d",rev)

prime or not:
n=int(input("enter any number:"))
count=0
if(n%2==0):
print("prime:")
count+1=1
else:
print("not prime:")

factorial of a number:

n=int(input("enter any number:"))
fact=1
for i in range(2,n+1):
fact=fact*i
print("fact of number is =%d",fact)

palindrome or not:
n=input("enter any string:")
if(n==n[::-1]):
        print("palindrome:")
else:
        print("not palindrome:")
        
        
check whether symbol is vowel or consonent:
x=input("enter a symbol:")
if x in ('a','e','i','o','u'):
  print("given symbol is ovel")
else:
    print("given symbol is consonent")




        
number of vowels in a string:
x=input("enter string:")
count=0
for ele in range(len(x)):
   if x[ele] in "aeiou":   
                   count+=1
print(count)

        
        
