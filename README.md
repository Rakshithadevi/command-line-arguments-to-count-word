# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Create a text file in a specific loaction of interest.
### Step 2: On the same location as the text file, create a python program file.
### Step 3: In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4: using read() and split(), split the lines in the file into a sequence of words.
### Step 5:using len() count the number of words in the text file.
### Step 6: In command prompt, initiate python followed by program name and text file name to get the output.

## PROGRAM:
```
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: RAKSHITHA DEVI
RegisterNumber:21005572
```
# in python file "program.py"
```
import sys
f1=open(sys.argv[1])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close()
```
### OUTPUT:
### program.py:
![image](https://user-images.githubusercontent.com/94165326/154830930-fc649952-97f4-4c0e-87bb-318b657a9074.png)


### file1.txt:
![image](https://user-images.githubusercontent.com/94165326/154830934-fcbdcc63-9249-433d-ab39-6ca3c82f71c0.png)


### terminal and command prompt:
![image](https://user-images.githubusercontent.com/94165326/154830940-d855df6f-8dd4-4664-ac9c-65e38aceefb4.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
