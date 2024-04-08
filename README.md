# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
Program to mark the maximum of marks using the list method sort
Developed by: KEERTHIVASAN M
RegisterNumber: 212223100021

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

iii) # To find the maximum marks without using builtin functions.
``` 
''' 
Program to the maximum marks without using builtin functions.
Developed by: KEERTHIVASAN M
RegisterNumber: 212223100021
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
    
```



## Output:

![Screenshot 2024-04-08 170221](https://github.com/rdxkeerthi/FindMaximum/assets/147473120/4ea531b0-d8ad-4eeb-b94e-07a15af3e1e1)

![Screenshot 2024-04-08 170313](https://github.com/rdxkeerthi/FindMaximum/assets/147473120/9218bab4-3a02-47c1-82bd-a0a82e8cf64f)

![Screenshot 2024-04-08 170427](https://github.com/rdxkeerthi/FindMaximum/assets/147473120/9fcf78a1-afa8-46bb-8f6d-62f26d842ad4)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
