Download Link: https://assignmentchef.com/product/solved-cs-315-homework-4
<br>
In this assignment you must <strong>not </strong>use your programming language support (nor any libraries) for arbitrary length arithmetic.

Some procedures that you created while solving Homework 2 may be useful in this assignment too.

<strong>Problem 1. </strong>Design and implement an algorithm that takes two non-negative binary integers <em>x </em>and <em>y </em>represented as in Homework 2 and returns the quotient and the remainder of the integer division of <em>x </em>by <em>y</em>. Assume that <em>y &gt; </em>0. Represent both the quotient and the remainder as vectors of binary integers. (You can implement the division algorithm from the textbook).

Test your program for the following binary integers <em>x </em>and <em>y</em>:

<ol>

 <li><em>x </em>= [0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1] and <em>y </em>= [1<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>1]</li>

 <li><em>x </em>= [1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1] and <em>y </em>= [0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>1]</li>

 <li><em>x </em>= [1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1] and <em>y </em>= [1<em>,</em>0<em>,</em>1<em>,</em>0<em>,</em>1<em>,</em>0<em>,</em>1<em>,</em>0<em>,</em>1<em>,</em>0<em>,</em>1<em>,</em>0<em>,</em>1<em>,</em>0<em>,</em>1].</li>

</ol>

<strong>Problem 2. </strong>Design and implement an algorithm that takes a positive integer <em>N </em>and two non-negative integers <em>x </em>and <em>y</em>, and returns <em>x<sup>y </sup></em>mod <em>N</em>. Assume that <em>x,y </em>≤ <em>N </em>− 1, and that, <em>N</em>, <em>x</em>, and <em>y </em>are represented as vectors of binary digits (like in Homework 2 and Problem 1).

Test your program for

<ol>

 <li><em>N </em>= [0<em>,</em>0<em>,</em>1<em>,</em>0<em>,</em>1] <em>x </em>= [0<em>,</em>1], <em>y </em>= [0<em>,</em>1<em>,</em>0<em>,</em>1]</li>

 <li><em>N </em>= [1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1] <em>x </em>= [1<em>,</em>0<em>,</em>1<em>,</em>1], <em>y </em>= [0<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1]</li>

 <li><em>N </em>= [1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>1], <em>x </em>= [1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1], <em>y </em>= [1<em>,</em>1<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1]</li>

</ol>

<strong>Problem 3. </strong>Test the performance (time in seconds) of your modular exponentiation program on integers of different sizes. Comment on how the performance of the program depends on the number of digits in the input vectors representing binary integers. Use the following test inputs:

<em>N </em>= [1<em>,</em>0<em>,</em>1<em>,n </em>0<sup>′</sup><em>s,n </em>1<sup>′</sup><em>s,</em>0<em>,</em>1]<em>,x </em>= [1<em>,</em>1<em>,n </em>0<sup>′</sup><em>s,n </em>1<sup>′</sup><em>s</em>]<em>,y </em>= [1<em>,</em>0<em>,n </em>0<sup>′</sup><em>s,n </em>1<sup>′</sup><em>s</em>]<em>,</em>

where <em>n </em>= 1<em>,</em>2<em>,</em>4<em>,</em>8<em>,</em>16<em>,</em>32<em>,</em>64<em>,</em>128 etc. Continue doubling <em>n </em>but stop when the time of a test exceeds 600 seconds. You may want to write a procedure that generates these vectors rather than have the user to type them in.

<strong>In your program you must not convert the input binary vectors representing numbers to decimals and use the built-in arithmetic operations on decimals. The operations must be performed on the binary vectors.</strong>

<strong>To write your programs you have to use one of the following programming languages: C/C++, Java, or Python 3.0 or higher.</strong>

<strong>Submit two files. One of them must contain the report in pdf format. The other one, submitted as a single .zip file, should contain the source codes (with adequate and clear comments) and, possibly, data sets.</strong>

<strong>In your report include a brief description of the algorithms you implemented, a list of test cases you tried and the results. The report should also contain compilation and execution instructions for your programs.</strong>