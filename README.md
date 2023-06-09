# command-line-arguments-to-count-word

## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.


## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7


## ALGORITHM:

### Step 1:
Import sys module

### Step 2:
Open the file with sys.argv[1]

### Step 3:
Use the for loop to select the content in file

### Step 4:
Use split function to to separate the file content into words or strings

### Step 5:
Count the length of the words using len

### Step 6:
Print the number of words




## PROGRAM:

```

Program for getting the word count from the contents of a file using command line arguments
Developed by:M.Harini
RegisterNumber: 212222240035

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)

```

### OUTPUT:

![image](https://github.com/Harinimuthu17/command-line-arguments-to-count-word/assets/130278614/fb447575-09d8-4a47-a60d-59c2dfed57e2)
![image](https://github.com/Harinimuthu17/command-line-arguments-to-count-word/assets/130278614/ebb7684e-a4e8-4eda-9209-6402987d79c2)
![image](https://github.com/Harinimuthu17/command-line-arguments-to-count-word/assets/130278614/ad4b980e-26c1-4337-a10a-893040cf6157)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
