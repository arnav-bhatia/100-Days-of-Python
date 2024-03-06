## Day 6 - Python Functions and Karel

### Day Challenge

I spent the entire section completing challenges in a website called [Reeborg's world](https://reeborg.ca/index_en.html) which helps students understand loops. 

For the day challenge, I was tasked with completing a tough challenge, for which I had to write code to ensure that the robot would reach the destination no matter where it spawned.

<img src="/Day-06/6-C.jpeg">

```python

def turn_right():
    turn_left()
    turn_left()
    turn_left()
    
while front_is_clear():
    move()
turn_left()

while not at_goal():
    if right_is_clear():
        turn_right()
        move()
    elif front_is_clear():
        move()
    else:
        turn_left()

```
### Day Exercises

<img src="/Day-06/6-1.jpeg">

```python

def turn_right():
    turn_left()
    turn_left()
    turn_left()
    
def jump():
    move()
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_left()
    
while not at_goal():
    jump()

```

<img src="/Day-06/6-2.jpeg">

```python

def turn_right():
    turn_left()
    turn_left()
    turn_left()
    
def jump():
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_left()
    
while not at_goal()::
    if wall_in_front():
        jump()
    else:
        move()

```

<img src="/Day-06/6-3.jpeg">

```python

def turn_right():
    turn_left()
    turn_left()
    turn_left()
    
def jump():
    turn_left()
    while wall_on_right():
        move()
    turn_right()
    move()
    turn_right()
    while front_is_clear():
        move()
    turn_left()
    
while not at_goal():
    if wall_in_front():
        jump()
    else:
        move()

```

