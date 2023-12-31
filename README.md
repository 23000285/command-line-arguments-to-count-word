# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Prompt for file name: Get the name of the file to count words in.

### Step 2: 
Initialize word count: Set a counter variable to 0. 

### Step 3: 
Open and process file: Open the specified file in read mode, iterate through each line, split it into words, and add the word count for each line to the total count.

### Step 4:  
Close file: Ensure the file is properly closed.

### Step 5: 
Print result: Display the total number of words found in the file.

## PROGRAM:
```
#Program to find the Word Count using command line arguments
#Developed by: VENKATANATHAN P R
#register Number: 23000285

fname=input("Enter the file name:")
num_words=0
with open(fname, 'r') as f:
    for line in f:
        words=line.split()
        num_words+=len (words)
print('Number of words: ',num_words)
```
### OUTPUT:
![image](https://github.com/23000285/command-line-arguments-to-count-word/assets/138970859/43b03b99-a4a6-4aaa-ae00-ddb6909906d3)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
