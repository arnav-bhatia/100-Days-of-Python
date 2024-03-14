## Day 13 - Debugging: How to Find and Fix Errors in your Code

### Day Exercises

I was given three different codes which contained bugs and were not working as intended. I was tasked with finding the bug(s) and fixing the code.

### Exercise 1

Provided Code containing unknown bug

```python

number = int(input())

if number % 2 = 0:
  print("This is an even number.")
else:
  print("This is an odd number.")

```

Debugged Code

```python

number = int(input())

if number % 2 == 0: #Changed '=' to '=='
  print("This is an even number.")
else:
  print("This is an odd number.")


```

### Exercise 2

Provided Code containing unknown bug

```python

year = input()

if year % 4 == 0:
  if year % 100 == 0:
    if year % 400 == 0:
      print("Leap year.")
    else:
      print("Not leap year.")
  else:
    print("Leap year.")
else:
  print("Not leap year.")


```

Debugged Code

```python

year = int(input()) # Wrapped the input function with an int converter

if year % 4 == 0:
  if year % 100 == 0:
    if year % 400 == 0:
      print("Leap year.")
    else:
      print("Not leap year.")
  else:
    print("Leap year.")
else:
  print("Not leap year.")



```

### Exercise 3

Provided Code containing unknown bug

```python

target = int(input())
for number in range(1, target + 1):
  if number % 3 == 0 or number % 5 == 0:
    print("FizzBuzz")
  if number % 3 == 0:
    print("Fizz")
  if number % 5 == 0:
    print("Buzz")
  else:
    print([number])


```

Debugged Code

```python

target = int(input())
for number in range(1, target + 1):
  if number % 3 == 0 and number % 5 == 0: # Changed 'or' to 'and'
    print("FizzBuzz")
  elif number % 3 == 0: #Changed if to elif
    print("Fizz")
  elif number % 5 == 0: #Changed if to elif
    print("Buzz")
  else:
    print(number) #Removed []

```

