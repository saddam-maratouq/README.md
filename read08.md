# Expressions and operators

## Operators
JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

For example, 3+4 or x*y.


A unary operator requires a single operand, either before or after the operator:



***Assignment operators*** 

*An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.*


***Loops and iteration***

Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript [guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) introduces the different iteration statements available to JavaScript.


* ***for statement***

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows: 

for ([initialExpression]; [conditionExpression]; [incrementExpression])

  statement


* ***while statment***

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while
 (condition){

  statement
 }

*** note : If  the  condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.***



* ***do...while statement***

The do...while statement repeats until a specified condition evaluates to false. 


do

 
  statement

while (condition);




 ***for...in statement ***

 The for...in statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements. A for...in statement looks as follows:

 for

  (variable in object)

  statement 





  ***for...of statement***

  The for...of statement creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property. 

  for
  
   (variable of object)

  statement



  ![wile vs for](https://i.pinimg.com/originals/c2/56/8f/c2568f7e6bc7af034e5f1c42d3747e64.png)

  



