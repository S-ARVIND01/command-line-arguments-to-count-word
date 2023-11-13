# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words.

### Step 6:
Run the program to determine the number of words in the file created.
## PROGRAM:
```python
import sys
count = 0
with open (sys.argv[1],'r') as f1:
    for line in f1:
        word = line.split()
        count += len (word)
print("word count in file = ",count)
```
### OUTPUT:

![282351312-172b24df-4ef4-41f5-a9fe-6efc3e8469f3](https://github.com/S-ARVIND01/command-line-arguments-to-count-word/assets/118707337/c4f9144b-43c0-410d-92eb-5f3b88550ff8)

![2](https://github.com/S-ARVIND01/command-line-arguments-to-count-word/assets/118707337/181b892b-099d-4e03-9d43-270f0efa4ffe)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
