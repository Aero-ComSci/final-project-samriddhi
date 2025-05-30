[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/DpCY8B3G)

Summer Fun Planner

Who is the program for?
For students who want to plan their summer break

What does the program do?
Helps students pick activities to do during summer and automatically picking something fun to do each day.

Screenshot:
https://drive.google.com/file/d/1euLiWO-zVGuqoDe4paTJjx45uFNtGW_f/view?usp=share_link

Recording:
https://drive.google.com/file/d/1XyeJc2EK7J-NGTeSSzV4nzeJ5D60XJRW/view?usp=share_link

```python

fun = ["swim", "bike ride", "video games", "sleep", "read", "hike", "go to beach"]
print("Here are fun things to do in summer:")
for f in fun:
    print(f)

days = int(input("How many summer days do you want to plan for? "))
for i in range(1, days + 1):
    print("Day", i, "have fun doing:", fun[i])

def get_activity():
    index = int(input("Pick a number 1 to 5: "))
    return fun[index-1]

print("Your activity for today is:", get_activity())

```
