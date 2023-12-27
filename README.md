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
Developed by:SRISHANTH J
RegisterNumber:212223240160
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python

'''
Program to find the maximum marks using the list method max().
Developed by:SRISHANTH J
RegisterNumber:212223240160
'''
def max_marks(marks):
    maxi=max(marks)
    return maxi
    
```
iii) # To find the maximum marks without using builtin functions.
```Python

'''
Program to the maximum marks without using builtin functions.
Developed by:SRISHANTH J
RegisterNumber:212223240160
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if(i>max):
            max=i
    return max
   

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
<img width="555" alt="Screenshot 2023-12-27 144314" src="https://github.com/srishanth2006/FindMaximum/assets/150319470/07a765b9-49a7-483a-9cc1-5bc0cf9cb018">
<img width="565" alt="Screenshot 2023-12-27 144442" src="https://github.com/srishanth2006/FindMaximum/assets/150319470/28295f9b-1c42-42b9-aebc-3546dc8f9767">
<img width="500" alt="Screenshot 2023-12-27 144455" src="https://github.com/srishanth2006/FindMaximum/assets/150319470/edd659db-b3dd-4424-9913-30d33a5417fe">

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
