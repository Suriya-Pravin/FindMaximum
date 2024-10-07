### Date : 
# Ex-6 : Find the maximum of a list of numbers
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
Program to find the square root for the given number(newton's method) using function.</br>
Developed by: Suriya Pravin M</br>
RegisterNumber : 212223230223</br></br>
i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(array):
    array.sort()
    return array[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(array):
    return max(array)

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1


```



## Output:
![1)](https://github.com/user-attachments/assets/9673fd62-b994-4198-adce-793c250948cb)
![2)](https://github.com/user-attachments/assets/2f3a61d4-9da2-4875-9be0-17cc593ed741)
![3)](https://github.com/user-attachments/assets/019d5c6e-36ac-4217-b169-154ae8c44502)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
