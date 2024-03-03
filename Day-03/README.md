## Day 3 - Control Flow and Logical Operators

### Day Challenge

I built a simple text based Treasure Island adventure. Your choices control your character's outcome.

Replit Link : https://replit.com/@soundwave274/Day-3-Treasure-Island

### Day Exercises

<img src="/Day-03/3-1.jpeg">

```python

# Which number do you want to check?
number = int(input())
# 🚨 Don't change the code above 👆

# Write your code below this line 👇
if number%2==0:
  print('This is an even number.')
else:
  print('This is an odd number.')
```

<img src="/Day-03/3-2.jpeg">

```python

# Enter your height in meters e.g., 1.55
height = float(input())
# Enter your weight in kilograms e.g., 72
weight = int(input())
# 🚨 Don't change the code above 👆

#Write your code below this line 👇
bmi = weight/(height**2)

if (bmi<18.5):
  print(f'Your BMI is {bmi}, you are underweight.')
elif (bmi<25):
  print(f'Your BMI is {bmi}, you have a normal weight.')
elif (bmi<30):
  print(f'Your BMI is {bmi}, you are slightly overweight.')
elif (bmi<35):
  print(f'Your BMI is {bmi}, you are obese.')
else:
  print(f'Your BMI is {bmi}, you are clinically obese.')
```

<img src="/Day-03/3-3.jpeg">

```python

# Which year do you want to check?
year = int(input())
# 🚨 Don't change the code above 👆

# Write your code below this line 👇
if year%4==0:
  if year%100==0:
    print('Not leap year')
    if year%400==0:
      print('Leap Year')
  print('Leap year')
else:
  print('Not leap year')
```

<img src="/Day-03/3-4.jpeg">

```python

print("Thank you for choosing Python Pizza Deliveries!")
size = input() # What size pizza do you want? S, M, or L
add_pepperoni = input() # Do you want pepperoni? Y or N
extra_cheese = input() # Do you want extra cheese? Y or N
# 🚨 Don't change the code above 👆
# Write your code below this line 👇
if size == 'S':
  bill = 15
elif size == 'M':
  bill = 20
else:
  bill = 25

if add_pepperoni == 'Y':
  if size == 'S':
    bill = 17
  else:
    bill+=3

if extra_cheese == 'Y':
  bill+=1

print(f'Your final bill is: ${bill}.')
```

<img src="/Day-03/3-5.jpeg">

```python

print("The Love Calculator is calculating your score...")
name1 = input() # What is your name?
name2 = input() # What is their name?
# 🚨 Don't change the code above 👆
# Write your code below this line 👇
name = name1 + name2
name = name.lower()

true = name.count('t') + name.count('r') + name.count('u') + name.count('e')
love = name.count('l') + name.count('o') + name.count('v') + name.count('e')

Score = true*10+love

if Score > 90 or Score < 10:
  print(f"Your score is {Score}, you go together like coke and mentos.")
elif Score < 50 and Score > 40:
  print(f"Your score is {Score}, you are alright together.")
else:
  print(f"Your score is {Score}.")
```
