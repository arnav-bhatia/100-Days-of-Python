## Day 8 - Function Parameters and Caesar Cipher

### Day Challenge

I built a program based on the caesar cipher which encrypts and decrypts your messages depending on the parameters you choose.

Replit Link : https://replit.com/@soundwave274/Day-8-Caesar-Cipher

### Day Exercises

<img src="/Day-08/8-1.jpeg">

```python

# Write your code below this line 👇
import math
def paint_calc(height, width, cover):
  cans = math.ceil((height*width)/cover)
  print(f"You'll need {cans} cans of paint.")  

# Write your code above this line 👆
# Define a function called paint_calc() so the code below works.   

# 🚨 Don't change the code below 👇
test_h = int(input()) # Height of wall (m)
test_w = int(input()) # Width of wall (m)
coverage = 5
paint_calc(height=test_h, width=test_w, cover=coverage)


```

<img src="/Day-08/8-2.jpeg">

```python

# Write your code below this line 👇
def prime_checker(number):
  is_prime = True
  for i in range(2,number):
    if number%i==0:
      is_prime = False
  if isP:
    print("It's a prime number.")
  else:
    print("It's not a prime number.")
# Write your code above this line 👆
    
#Do NOT change any of the code below👇
n = int(input()) # Check this number
prime_checker(number=n)


```

