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
Program to mark the maximum of marks using the list method sort
Developed by: your name: Vineesh.M
RegisterNumber: 21004131

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: your name: Vineesh.M
RegisterNumber: 21004131

def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1 = i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])



```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: your name: Vineesh.M
RegisterNumber: 21004131

def max_marks(marks):
    a=max(marks)
    return a


```
 

## Output:
![ex7](https://user-images.githubusercontent.com/93427254/148632379-213434b9-68fe-4dd8-8640-429e221780ab.png)
![ex7a](https://user-images.githubusercontent.com/93427254/148632384-31513c35-a454-4e67-bf65-9a34f1f193f9.png)
![ex7b](https://user-images.githubusercontent.com/93427254/148632389-bd844144-a9b0-457c-8acd-96974bb1e681.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
