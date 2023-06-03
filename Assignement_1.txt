# Assignment 1

1. In the below elements which of them are values or an expression? eg:- values can be
  integer or string and expressions will be mathematical operators.

Values: 'hello', -87.8, 6
Expression: *, -, /, +

2. String vs Variable

String: A string is a data type that represents array of charecters. The charecters are enclosed withiin double quotes ("") and sometimes single quotes('').
Ex: "name"

Variable: A variable is just a place holder for a value of any type(string, int, bool) with a name assigned.
Ex: x = 10

3. Describe 3 diffident data type?

Int: An interger is a data type used to represent whole numbers(0..n). Integer can be classified as positive and negative integers. So it can represent upto (-n..0..n). Different language assign different no of bits like 32bit, 64 bit.

Ex: 10, -100

String: A string is a data type that represents array of charecters. The charecters are enclosed withiin double quotes ("") and sometimes single quotes('').

Ex: "apple", 'lime'

Bool: A boolean is a data type which represnets  a binary truth values such as True, and False or 0 and 1.
 It's useful in programming to make logical conditions like in `if` statements. A variable can also hold a bool value.

 Ex: is_human = True


```python
x = 5
y = 10

if x < y:
    print("x is less than y")
else:
    print("x is not less than y")
```

4. An expression is made upon operators, variables/symbols, and numbers. All expression have the same goal just to evaluate/compute a statement.


Ex: x + 9

5.  statement vs expression

The purpose of an assignment statement is to assign a value to a variable like here spam = 10.
It does not produce any value. It just assigns 10 to spam.

Expressions on the other hand do produce a value.

Ex: 10 + 100

The above expression produce a value which is 110 by adding two integers.

6. bacon = 23

7. 

'spam' + 'spamspam' = 'spamspamspam'

'spam' * 3  = 'spamspamspam'

8. A variable should starts with a letters only  while 100 is an invalid variable name because it starts with a number.

9. we can use int(), float(), str() functions to get the respective values of a value.

Ex: x = '100'
    int(x)

10. 'I have eaten'+ 99 + 'burritos'. This expression will cause  a TypeError. We can fixit by using str().

'I have eaten'+ str(99) + 'burritos'.

And it will produce this value 'I have eaten99burritos' .


