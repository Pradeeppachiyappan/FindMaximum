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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Pradeep Raj P
RegisterNumber: 212222240073
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
test1=[88, 67, 77, 93, 95, 11, 67, 89, 56, 89]
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Pradeep Raj P 
RegisterNumber: 212222240073
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
test1=[88, 67, 77, 93, 95, 11, 67, 89, 56, 89]

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
### output 1:
![Screenshot (71)](https://github.com/Pradeeppachiyappan/FindMaximum/assets/118707347/efab58a5-ff07-47ff-891f-bd8e08fc9cc9)
### output 2:
![Screenshot (72)](https://github.com/Pradeeppachiyappan/FindMaximum/assets/118707347/adf6fa0d-7339-4e1e-b7b0-d6082d9cf213)
### output 3:
![Screenshot (73)](https://github.com/Pradeeppachiyappan/FindMaximum/assets/118707347/32b9be7f-c070-4d8b-9986-5ad99808d7f8)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
