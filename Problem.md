# Pseudocode solutions to different problems
## Display student information using different data types
```
DECLARE Name, StdID: STRING
DECLARE Age: INTEGER
DECLARE Section: CHAR
DECLARE Marks: REAL

Name <-- "Ayan Gul Memon"
StdID <-- "26K-2060"
Age <-- 19
Section <-- 'B'
Marks <-- 87.9

OUTPUT "Student Name: ", Name
OUTPUT "Student ID:", StdID
OUTPUT "Age: ", Age
OUTPUT "Section: ", Section
OUTPUT "Marks: ", Marks
```
## Read and display a character using getchar() and putchar()
```
DECLARE chr: CHAR
OUTPUT "Please enter a character"
getchar()
OUTPUT "You entered the character:"
putchar()
```
## Display a floating-point value using different precision settings
```
DECLARE value: REAL
OUTPUT "Value as a whole number", ROUND(value, 0)
OUTPUT "Value to two d.p:", ROUND(value, 2)
OUTPUT "Value to four d.p", ROUND(value, 4)
OUTPUT "Value to six d.p", ROUND(value, 6)
```
