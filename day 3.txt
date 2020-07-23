#!/usr/bin/env python
# coding: utf-8

# In[13]:


"""Question 1 : Find sum of n numbers with help of While loop"""
    
n = 10
sum = 0
for num in range(0, n+1, 1):
    sum = sum+num
print("SUM of first ", n, "numbers is: ", sum )


# In[19]:


"""Question 2 : Program to check if a number is prime or not"""

num = 407

# To take input from the user
#num = int(input("Enter a number: "))

# prime numbers are greater than 1
if num > 1:
   # check for factors
   for i in range(2,num):
       if (num % i) == 0:
           print(num,"is not a prime number")
           print(i,"times",num//i,"is",num)
           break
   else:
       print(num,"is a prime number")
       
# if input number is less than
# or equal to 1, it is not prime
else:
   print(num,"is not a prime number")


# In[ ]:




