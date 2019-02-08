

# Question 54

### **Question**

> ***Assuming that we have some email addresses in the "username@companyname.com" format, please write program to print the company name of a given email address. Both user names and company names are composed of letters only.***

> ***Example:
If the following email address is given as input to the program:***
```
john@google.com
```
> ***Then, the output of the program should be:***
```
google
```
> ***In case of input data being supplied to the question, it should be assumed to be a console input.***

----------------------
### Hints 
> ***Use \w to match letters.***

----------------------

**Main author's Solution: Python 2**
```python
import re
emailAddress = raw_input()
pat2 = "(\w+)@(\w+)\.(com)"
r2 = re.match(pat2,emailAddress)
print r2.group(2)
```
----------------
**My Solution: Python 3**
```python
#to be written

```
---------------------


# Question 55

### **Question**

>***Write a program which accepts a sequence of words separated by whitespace as input to print the words composed of digits only.***

>***Example:
If the following words is given as input to the program:***
```
2 cats and 3 dogs.
```
>***Then, the output of the program should be:***
```
['2', '3']
```
>***In case of input data being supplied to the question, it should be assumed to be a console input.***


----------------------
### Hints 
> ***Use re.findall() to find all substring using regex.***

----------------------

**Main author's Solution: Python 2**
```python
import re
s = raw_input()
print re.findall("\d+",s)
```
----------------
**My Solution: Python 3**
```python
#to be written

```
---------------------



# Question 56

### **Question**

> ***Print a unicode string "hello world".***

----------------------
### Hints 
> ***Use u'strings' format to define unicode string.***

----------------------

**Main author's Solution: Python 2**
```python
unicodeString = u"hello world!"
print unicodeString
```
----------------
**My Solution: Python 3**
```python
#to be written

```
---------------------

# Question 57

### **Question**

> ***Write a program to read an ASCII string and to convert it to a unicode string encoded by utf-8.***

----------------------
### Hints 
> ***Use unicode() function to convert.***

----------------------

**Main author's Solution: Python 2**
```python
s = raw_input()
u = unicode( s ,"utf-8")
print u
```
----------------
**My Solution: Python 3**
```python
#to be written

```
---------------------

# Question 58

### **Question**

> ***Write a special comment to indicate a Python source code file is in unicode.***

----------------------
### Hints 
> ***Use unicode() function to convert.***

----------------------

**Solution:**
```python
# -*- coding: utf-8 -*-
```
----------------
# Question 59

### **Question**

>***Write a program to compute 1/2+2/3+3/4+...+n/n+1 with a given n input by console (n>0).***

>***Example:
If the following n is given as input to the program:***
```
5
```
>***Then, the output of the program should be:***
```
3.55
```
>***In case of input data being supplied to the question, it should be assumed to be a console input.***


----------------------
### Hints 
> ***Use float() to convert an integer to a float***

----------------------

**Main author's Solution: Python 2**
```python
n=int(raw_input())
sum=0.0
for i in range(1,n+1):
    sum += float(float(i)/(i+1))
print sum
```
----------------
**My Solution: Python 3**
```python
#to be written

```
---------------------
