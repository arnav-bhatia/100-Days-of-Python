## Day 4 - Randomisation and Python Lists

### Day Challenge

I built a rock-paper-scissors game.

Replit Link : https://replit.com/@soundwave274/Day-4-Rock-Paper-Scissors

### Day Exercises

<img src="/Day-04/4-1.jpeg">

```python

# Write your code below this line 👇
# Hint: Remember to import the random module first. 🎲
import random
num = random.randint(1,2)
if num%2==0:
  print('Heads')
else:
  print('Tails')
```

<img src="/Day-04/4-2.jpeg">

```python

names = names_string.split(", ")
# The code above converts the input into an array seperating
#each name in the input by a comma and space.
# 🚨 Don't change the code above 👆
import random
index = random.randint(0, len(names)-1)
print(f'{names[index]} is going to buy the meal today!')
```

<img src="/Day-04/4-3.jpeg">
<img src="/Day-04/4-4.jpeg">


```python

line1 = ["⬜️","️⬜️","️⬜️"]
line2 = ["⬜️","⬜️","️⬜️"]
line3 = ["⬜️️","⬜️️","⬜️️"]
map = [line1, line2, line3]
print("Hiding your treasure! X marks the spot.")
position = input() # Where do you want to put the treasure?
# 🚨 Don't change the code above 👆
# Write your code below this row 👇
abc = ['A', 'B', 'C']
col = abc.index(position[0])
row = int(position[1])

map[row-1][col] = 'X'

# Write your code above this row 👆
# 🚨 Don't change the code below 👇
print(f"{line1}\n{line2}\n{line3}")
```

