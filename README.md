# 19CS301-Module33
Exp.No:3(a)	STRING- FIND AND REPLACE
### AIM
To write a python function to accept a string, word to be replaced and replace the words of the string, get the new word to be replaced from the user.
### ALGORITHM
Step 1:	 Begin the program.

Step 2:	 Input the original string (str1) and the word to replace (replace_str)

Step 3:	 Ask the user to input the replacement word (str2).

Step 4:	 Replace all occurrences of replace_str in str1 with str2 using replace() method in Python.

Step 5:	 The modified string is stored in str3.

Step 6:	 Display the original string (str1) to show the user the initial string.

Step 7:	 Display the modified string (str3) to show the user the string after the replacement.

Step 8:	 Terminate the program.

### PROGRAM
```def replacestr(str1,replace_str):
    str2=input()
    str3=str1.replace(replace_str,str2)
    print(f"The old string is {str1}\nthe new string is {str3}")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/ab789972-0bcc-4de6-a234-f80f5209ed92)

### RESULT
Thus the python program of find and replace is implemented and executed successfully.


Exp.No:3(b)	REGEX-PATTERN MATCHING USING REGEX

### AIM
To write a Python program that matches a string that has an a followed by two to three 'b'.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept a string str1 from the user.

Step 3:	 Define a regular expression pattern as r"[a]+b{2,3}".

Step 4:	 Use the re.match() function to check if the string str1 matches the given pattern. If the string str1 matches the pattern, proceed to step 5. Else If the string str1 does not 
          match the pattern, proceed to step 6.

Step 5:	 Print "Found a match!" if the string matches the pattern.

Step 6:	 Print "Not matched!" if the string does not match the pattern.

Step 7:	 Terminate the program.

### PROGRAM
```import re
str1=input()
pattern=r"[a]+b{2,3}"
if re.match(pattern,str1):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/b473b268-4127-4409-9985-e43d47b02847)

### RESULT
Thus the python program for pattern matching using regular expression was  implemented and executed successfully.

Exp.No:3(c)	LIST- EVEN NUMBERS LIST

### AIM
To write a python function that accepts N and to create a list with even numbers up to N.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer a.

Step 3:	 Create an empty list l.

Step 4:	In For Loop, Iterate through the numbers from 1 to a-1.For each number i, check if i is even: If i % 2 == 0, append i to the list l.

Step 5:	 Print the list l which contains all even numbers from 1 to a-1.

Step 6:	 Terminate the program.
### PROGRAM
```def createlist(a):
    l=[]
    for i in range(1,a):
        if (i%2==0):
            l.append(i)
    print(l)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/a21369b0-1967-4362-b91f-84bb82becbcd)

### RESULT
Thus the python program for printing a list with even numbers up to n, was implemented and executed successfully.

Exp.No:3(d)	TUPLES- A TUPLE WITH MULTIPLES OF 5
### AIM
To write a python program to create the tuple by the multiples of 5 up to N. Get the N value from the user.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer N from the user.

Step 3:	 Define an empty tuple multiples_of_5.

Step 4:	 Loop through the numbers starting from 5, up to N-1 (not including N), with a step size of 5 For each value of i, add i to the tuple multiples_of_5.

Step 5:	 Return the multiples_of_5 tuple.

Step 6:	 print the resultant tuple.

Step 7:	 Terminate the program.
### PROGRAM
```
def create_tuple(N):
    multiples_of_5 = tuple(i for i in range(5, N, 5))
    return multiples_of_5
N = int(input())
result = create_tuple(N)
print(f"{result}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/a16820ca-d669-4520-b141-c4e0a836c910)


 
### RESULT
Thus the python program for printing a tuple with numbers that are multiples of 5 up to n, was implemented and executed successfully.

Exp.No:3(e)	SEB- STRING SLICING
### AIM
To write a python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Take a slice of input_string starting from index 2 up to index 10.

Step 3:	 Reverse the substring.

Step 4:	 slice the reversed string, extracting every second character, starting from the first.

Step 5:	 Print the sliced string in the above step.

Step 6:	 Terminate the program.
### PROGRAM
```
def slice(input_string):
    substring = input_string[2:10:]
    reversed_substring = substring[::-1]
    print(f"The reversed string is '{reversed_substring[::2]}'")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/1c3e5d33-4525-44e9-93c4-3431af135a04)

### RESULT
Thus the python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string was implemented and executed successfully.









