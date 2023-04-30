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
```
''' 

Developed by:M.PRAKASH 
RegisterNumber: 212222100035
'''
def max_marks(marks):
    marks.sort(reverse=True)
    return(marks[0])
    
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Developed by: M.PRAKASH
RegisterNumber: 212222100035
'''
def max_marks(marks):
    large=max(marks)
    return(large)



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Developed by:M.PRAKASH 
RegisterNumber: 212222100035
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
    
```
## Output:
<img width="659" alt="image" src="https://user-images.githubusercontent.com/118350045/235359109-1f0c861b-742c-4edb-8760-de29320d289b.png">
<img width="658" alt="image" src="https://user-images.githubusercontent.com/118350045/235359168-e71d48d0-e11f-4b91-a6e2-b45c97685d0a.png">
<img width="659" alt="image" src="https://user-images.githubusercontent.com/118350045/235359252-a5699b68-fb9b-4518-9700-01bdf2c6f2c8.png">

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
