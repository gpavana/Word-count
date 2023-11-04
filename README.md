# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
Open then required file by using the function"with"
### Step 2: 
 Using split function to split the words.
### Step 3: 
Finding the length of the words by using len() function.
### Step 4:  
Calling the function and printing the number of words.

## PROGRAM:
```
##REGISTER NO:212222230105
##NAME:PAVANA.G
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of words:",wordslen)
```
### FILE CONTENT:
![Screenshot (233)](https://github.com/gpavana/Word-count/assets/118787343/58ceb62b-e853-44e0-9812-f2719673dedf)
### OUTPUT:
![Screenshot (234)](https://github.com/gpavana/Word-count/assets/118787343/a1f02d0e-d246-4861-b8a3-3b4e42303115)

## RESULT:
Thus the program is written to find the word count from a text.
