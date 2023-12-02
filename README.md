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
```Python
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
i)![image](https://github.com/23008344/FindMaximum/assets/145742655/50540b33-1d7d-498e-b53d-9063a24c0c74)


## Output:
i)
![image](https://github.com/23008344/FindMaximum/assets/145742655/ac8e3347-a6d4-4c94-a58f-5e4893e4141a)

ii)
![image](https://github.com/23008344/FindMaximum/assets/145742655/1047f185-8914-45e3-903e-3a188a611e9a)

iii)
![image](https://github.com/23008344/FindMaximum/assets/145742655/3d41207c-7d35-42fa-a86d-0355f6db099b)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
