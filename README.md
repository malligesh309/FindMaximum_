# Ex - 6 Find the maximum of a list of numbers 
# Aim :
To write a program to find the maximum of a list of numbers.
# Equipment’s required :
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
# Algorithm :
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
# Program :
## i) To find the maximum of marks using the list method sort
```
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```
## ii) To find the maximum marks using the list method max()
```
def max_marks(marks):
    large = max(marks)
    return large
    
```

## iii) To find the maximum marks without using builtin functions
```
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        
```
# Output :
## i) To find the maximum of marks using the list method sort

![image](https://github.com/user-attachments/assets/3b3f180a-20d6-48be-a849-edcf007ff81c)


## ii) To find the maximum marks using the list method max()
![image](https://github.com/user-attachments/assets/0b8205d9-c7c3-403c-96ad-3a151c7eb943)


## iii) To find the maximum marks without using builtin functions

![image](https://github.com/user-attachments/assets/3c961d70-13d2-4e47-a469-04eef39c7d35)


# Result :
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
