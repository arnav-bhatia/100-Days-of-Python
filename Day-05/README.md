## Day 5 - Python Loops

### Day Challenge

I built a simple password generator which takes the number of letters, symbols and numbers you want in your password as inputs and returns a password which matches all your requirements.

Replit Link : https://replit.com/@soundwave274/Day-5-Password-Generator

### Day Exercises

<img src="/Day-05/5-1.jpeg">

```python

# Input a Python list of student heights
student_heights = input().split()
for n in range(0, len(student_heights)):
student_heights[n] = int(student_heights[n])
# 🚨 Don't change the code above 👆

# Write your code below this row 👇
total = 0
count = 0
for student in student_heights:
total += student
count += 1

avg = round(total/count)

print(f'''total height = {total}
number of students = {count}
average height = {avg}''')

```

<img src="/Day-05/5-2.jpeg">

```python

# Input a list of student scores
student_scores = input().split()
for n in range(0, len(student_scores)):
student_scores[n] = int(student_scores[n])

# Write your code below this row 👇
highest = 0
for score in student_scores:
if score > highest:
highest = score
print(f"The highest score in the class is: {highest}")

```

<img src="/Day-05/5-3.jpeg">

```python

target = int(input()) # Enter a number between 0 and 1000
# 🚨 Do not change the code above ☝️

# Write your code here 👇
sum = 0
for i in range(target+1):
if i%2==0:
sum+=i

print(sum)

```

<img src="/Day-05/5-4.jpeg">

```python

# Write your code here 👇
for i in range(1,101):
if (i%3==0 and i%5 ==0):
print('FizzBuzz')
elif i%3==0:
print('Fizz')
elif i%5==0:
print('Buzz')
else:
print(i)

```
