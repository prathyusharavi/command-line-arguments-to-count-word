# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import the sys module.

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1].

 
### Step 3:

Read the file using read() method.

### Step 4: 

Use split() method to split the file content into words.

### Step 5: 

Use len() to find the total words.

### Step 6:

Run the program to determine the number of words in the file.

## PROGRAM:
```
Developed by :YENUGANTI PRATHYUSA
Registered number : 23009045

import sys
count = 0
with open (sys.argv[1],'r') as f1:
    for line in f1:
        word = line.split()
        count += len (word)
print("word count in file = ",count)
```

### OUTPUT:
TEXTFILE:

  ![image](https://github.com/prathyusharavi/command-line-arguments-to-count-word/assets/147474424/a9af723c-dbf5-4284-9418-4af624dceba4)
PYTHONFILE:

  ![image](https://github.com/prathyusharavi/command-line-arguments-to-count-word/assets/147474424/21225931-d9ec-4f2a-af4a-864484e1bf00)
  ![image](https://github.com/prathyusharavi/command-line-arguments-to-count-word/assets/147474424/76c8c0b2-a574-40a8-b2ea-2e6b0fe0fdaf)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
