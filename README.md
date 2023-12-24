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
 Program for getting the word count from the contents of a file using command line arguments
 
 Developed by: Yamuna M
 
 RegisterNumber: 212223230248
 
```
import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```
### OUTPUT:
![Screenshot 2023-12-24 124529](https://github.com/yamunadass/command-line-arguments-to-count-word/assets/138971172/65c0bb45-0413-4343-9666-4f099283918f)
![image](https://github.com/yamunadass/command-line-arguments-to-count-word/assets/138971172/57bc04c5-a87b-45d1-b6e6-bbbc4495df2a)
![image](https://github.com/yamunadass/command-line-arguments-to-count-word/assets/138971172/84fe8dcf-28f8-457a-8302-a1ceb46c185a)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
