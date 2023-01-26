# Word-count

## AIM:

To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:

initialise the program with num_word=0

### Step 2: 

open the file with .csv extension in read mode
 
### Step 3: 

using for loop split the words

### Step 4:  

store the number of words splitted in num_words

### Step 5: 

using print() display the output

### Step 6: 

End of the program

## PROGRAM:
```
'''
developed by : Tejusve Kabeer.F
reference.no : 22002543
'''
num_words=0
with open('exp1.py','r') as file:
    for i in file:
        word=i.split()
        num_words+=len(word)
print("The number of words is:",num_words)
```

### OUTPUT:
![wrdcnt](https://user-images.githubusercontent.com/118364993/214785250-2c8a22d8-ac24-4ebf-b55d-0ddb79bec55c.png)

## RESULT:
Thus the program is written to find the word count from a text.
