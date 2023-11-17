# Exp-3a-Find the maximum of a list of numbers
## Date-05.09.2023
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
Program to mark the maximum of marks using the list method sort
Developed by: KISHORE KUMAR U
RegisterNumber:23000800
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: KISHORE KUMAR U
RegisterNumber: 23000800
'''
def max_marks(marks):
    # write your code here
    maxx=max(marks)
    return maxx


```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: KISHORE KUMAR U
RegisterNumber: 23000800
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/Kishorekumar22060/FindMaximum/assets/141472136/fa7d86aa-4756-433f-9a18-c9945a285f61)

![image](https://github.com/Kishorekumar22060/FindMaximum/assets/141472136/5a1b2789-f332-41df-aa55-6b8d731a15ce)

![image](https://github.com/Kishorekumar22060/FindMaximum/assets/141472136/332bc1fd-4a84-4b97-a761-79bae53cf069)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
