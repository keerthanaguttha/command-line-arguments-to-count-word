# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
Then declare count is equal to 0
### Step 3: 
read the file with python file name
### Step 4:  
splitting the word
### Step 5: 
After splitting count the number of words in the line
### Step 6: 
In last statement give the print statement
## PROGRAM:
```
'''
Developed by : GUTTHA KEERTHANA
Registered number : 212223240045
'''
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```


### OUTPUT:
![](5b2.jpg)
![](5b1.png)
![](5b3-1.jpg)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
