# DATE:
# EXP.NO:09
# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np

### Step 2:
Enter the input values

### Step 3:
Write python program for getting the word count from the contents of a file using command line arguments

### Step 4:
Run the program

### Step 5:
Input the values

### Step 6:
End the program

## PROGRAM:
#program to find the number of words in a text file</br>
#NAME: RUDESH KANNA R</br>
#REGISTER NUMBER: 24900303</br>
```
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/3e16fa9c-c508-4777-8561-0704065d29d7)



## RESULT:
Thus the program is written to find the word count from a text.
