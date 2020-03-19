[Return Home](https://lindseyshepard.github.io/learning-journal-repo/) 

# Comparison Operators: Evaluating Conditions

You can compare a situation by comparing one value in the script to what you expect it might be. The result will be a **Boolean**: _true_ or _false_

Operator | Symbol | Example
-------- | --------- | ------------- 
== | IS EQUAL TO, thisoperator compares two values (numbers, strings or booleans to see if they are the same) | 'hello' == 'hello' _true_  
!= | IS NOT EQUAL TO, this operator compares two values (number strings or booleans ) to see if they are _not the same_ | 'hello' != 'goodbye' _true_
=== | STRICT TO EQUAL, compares both value and data type of the same | '3' === 3 _false_ BUT '3' === '3' _true_
!== | STRICT NOT EQUAL TO, this checks to see if data type and value are not the same | '3' !== 3 _true_  
> | greater then | 3 > 4 _false_  
< | LESS then | 3 < 4 _true_  
>= | greater or equal then | 4 >=3 _true_ 
<= | Less then or equal to | 4<=3 _false_  


# Logical Operators

Comparison operators usually return single values or _true_ or _false_. Logical operators allow you to compare the result of more than one comparison operator. 
> (( 5 < 2 ) && ( 2 >= 3)) Expression 1 - Logical Operator - Expression 2  

Logical Operator | Symbol 
--------- | ----------
&& | Logical And  
|| | Logical Or  
! | logical not  

**Short-circuit Evaluation**
 These expressions are evaluated from left to right. If the first condition can provide enough information to get the answer, then there is no need to evaluate the second condition.
 > false && anything _it has found a false_
 > true || anything _it has found a true_  


 # Loops on Loops on Loops

 Loops: Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it is still true. the code block will run again. It repeats until the condition returns false. 
 > For loop, While Loop, and Do while are the 3 most common loops


 Loop Counters: A for loop uses a counter as a condition. This instructs the code to run a specified number of times. Here you can see the condition is made up of three statements. 
 > Initialization, Condition, and update.
 >(var i = 0; i < 10; i++);


 While Loops: As long as the condition is true it will loop.
 > while ( i < 10 )
 >Pro Tip: The difference between a While and a Do while. Is a Do while with always loop at least once regardless if the condition is true and a while loop will only execute if the condition is true


