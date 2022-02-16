# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open visual studio code.

### Step 2:
Create file with .py extension.
 
### Step 3: 
Start the program. 

### Step 4:
Write the code.

### Step 5: 
Run terminal for output of the given program.

### Step 6: 
End the program.

## PROGRAM:
~~~
# Developed by Vineesh.M
# Reference no: 21004131
# To write a program for getting the word count from a file.

num_of_words = 0
file = open('wordtext.txt')
wordtext = file.read()
words = wordtext.split()
num_of_words = len(words)
print("Number of words = ",num_of_words)
~~~

### OUTPUT:
![Screenshot (52)](https://user-images.githubusercontent.com/93427254/151340357-4bc012e8-8508-41d1-a1a6-2bd4d99961ce.png)
![Screenshot (53)](https://user-images.githubusercontent.com/93427254/151340378-5e4eff15-f7dd-4ac5-93b6-05b90fed1a45.png)


## RESULT:
Thus the program is written to find the word count from a file.
