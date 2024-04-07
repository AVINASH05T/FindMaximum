# EXPERIMENT: 6
# Find the maximum of a list of numbers
## NAME: AVINASH T
## REG NO: 212223230026
## DEPT:ARTIFICIAL INTELLIGENCE AND DATA SCIENCE
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
#Program Developed by: AVINASH T
#Register No:212223230026
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
![image](https://github.com/AVINASH05T/FindMaximum/assets/151514286/d9b6cbda-10e1-4732-b36a-45aab28113ee)
ii)	# To find the maximum marks using the list method max().
```Python
#Program Developed by: AVINASH T
#Register No:212223230026
def max_marks(marks):
    max_marks=max(marks)
    return max_marks
```
![image](https://github.com/AVINASH05T/FindMaximum/assets/151514286/08540aa6-1e36-4ea6-b8fc-e81d14577a82)
iii) # To find the maximum marks without using builtin functions.
```Python
#Program Developed by: AVINASH T
#Register No:212223230026
def max_marks(marks):
    max= marks[0]
    for i in marks[1:]:
        if i > max:
            max = i
    return max
```
![image](https://github.com/AVINASH05T/FindMaximum/assets/151514286/857f0900-1e7a-4b29-8482-f06404cb4ffb)
## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/AVINASH05T/FindMaximum/assets/151514286/e7ccf7f5-4988-438b-b64e-cca28bfb88d9)
ii)	# To find the maximum marks using the list method max().
![image](https://github.com/AVINASH05T/FindMaximum/assets/151514286/661310a9-ec15-404a-bec2-b288b0a1a06b)
iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/AVINASH05T/FindMaximum/assets/151514286/8c5ae5ee-a462-4432-8c9f-5d346b4264bc)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
