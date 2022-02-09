# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy.
### Step 2: 
Open using with keyword.
 ### Step 3: 
 Use split function to split words.
### Step 4:  
Store it in a variable.
### Step 5: 
Use for loop to proceed.
### Step 6: 
Print the result.

## PROGRAM:
```
#Name:J.Archana priya
#Reg.no:212221230007
import sys
count=0
with open (sys.argv[1],'r') as f1:
    data=f1.read()
    words=data.split()
for i in words:
     count+=1
print("It is:",count)
```

### OUTPUT:
![result](./result.png)
![textfile](./textfile.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
