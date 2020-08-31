# Python-program-to-check-whether-a-number-is-Prime-or-not.py
n=int(input())
if n<0:
    print(n, "is not a prime number")
  
# If num is greater than 1 
else : 
   for i in range(2, n):
       if (n % i) == 0:
           print(n, "is not a prime number")
           break
   else: 
       print(n, "is a prime number") 
  
