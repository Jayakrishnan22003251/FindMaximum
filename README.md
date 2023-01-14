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
      Developed by: JAYAKRISHNAN L B L
      RegisterNumber: 22003251

i)	# To find the maximum of marks using the list method sort.
```Python
       def max_marks(marks):
           marks.sort()
           a=marks[-1]
           return a



```

ii)	# To find the maximum marks using the list method max().
```Python
       def max_marks(marks):
           a=max(marks)
           return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
       def max_marks(list1):
           a=max(list1)
           return a


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
   ![image (2)](https://user-images.githubusercontent.com/120232371/212459575-daaa50b7-9cfb-4d24-b7f5-e8dde92adb5a.png)
   ![image (3)](https://user-images.githubusercontent.com/120232371/212459703-35f342ab-02e9-44de-884d-15a8f99848ac.png)
   ![image (4)](https://user-images.githubusercontent.com/120232371/212459770-82529637-9ec9-4988-8232-8e8c107456ee.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
