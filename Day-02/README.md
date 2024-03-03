## Day 2 - Understanding Data Types and How to Manipulate Strings

### Day Challenge

I made a simple bill calculator which receives the total bill as an input and prints you portion of the bill depending on the tip you want to leave and the number of people dining.

Replit Link : [https://replit.com/@soundwave274/Day-1-Band-Name-Generator](https://replit.com/@soundwave274/Day-2-Bill-Calculator)

### Day Exercises

<img src="/Day-02/2-1.jpeg">

```python

two_digit_number = input()
# 🚨 Don't change the code above 👆
####################################
# Write your code below this line 👇
two_digit_number = int(two_digit_number)
first_digit = two_digit_number//10
second_digit = two_digit_number%10
print(first_digit + second_digit)
```

<img src="/Day-02/2-2.jpeg">

```python

# 1st input: enter height in meters e.g: 1.65
height = input()
# 2nd input: enter weight in kilograms e.g: 72
weight = input()
# 🚨 Don't change the code above 👆

# Write your code below this line 👇
bmi = int(weight)/(float(height)**2)
print(int(bmi))
```

<img src="/Day-02/2-3.jpeg">

```python

age = input()
# 🚨 Don't change the code above 👆
# Write your code below this line 👇
years_left = 90 - int(age)
weeks_left = years_left*52
print(f'You have {weeks_left} weeks left.')

#weeks_left = years_left*52 + (years_left/4). This roughly accounts for leap years
```
