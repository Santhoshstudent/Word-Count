# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
Developed by: santhosh kumar B

Register no: 212223230193

def wordcount(filename):

    fp=open(filename)
    
    wordcount=0
    
    for i in fp:
    
        words=i.split()
        
        wordcount+=len(words)
        
    print("Total no of words in file is",wordcount)
    
    fp.close()
    
wordcount(input("Enter a filename in current directory or specify it with full path:"))

### OUTPUT:

![image](https://github.com/Santhoshstudent/Word-Count/assets/145446853/7ac7b5e4-a6be-4912-aa35-eaefb088d5f8)




## RESULT:
Thus the program is written to find the word count from a text.
