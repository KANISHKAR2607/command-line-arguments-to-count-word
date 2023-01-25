# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Import sys
### Step 2:

Initially make count = 0
### Step 3:

Open the content file using command line arguments.
### Step 4:

By using for loop name the function as "line"
### Step 5:

Split the line using .split
### Step 6:

Count the length of the word and print it

## PROGRAM:

```
#Developed by:KANISHKAR M
#ROLL NO:22007816

import sys
count=0
with open(sys.argv[1],'r') as f:
        for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)
```

### OUTPUT:

![5b pic](https://user-images.githubusercontent.com/118886772/214646546-06b7a413-4f7e-4964-a8f7-db7b30efda75.png)
![KAN 5B](https://user-images.githubusercontent.com/118886772/214646581-5e70cfb2-3acf-42eb-9423-457ea924fe42.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
