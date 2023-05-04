Download Link: https://assignmentchef.com/product/solved-csc2002s-assignment-5-architecture
<br>
This assignment is about assembly language programming using a MIPS simulator called SPIM. SPIM runs assembly language programs written for processors that implement the MIPS32 architecture. You may have to refer to  the appendix on Assemblers, Linkers, and the SPIM Simulator in Patterson+Hennessy Computer Architecture book (a copy of the appendix has been uploaded onto the course site).

Question 1

Write a program (<strong>question1.asm</strong>) to enter a series of 5 arbitrary strings and then print them out.  Store the strings in memory.

Question 2

Write a program (<strong>question2.asm</strong>) to convert a string into an integer. Assume that your input string is prefixed with an arbitrary non-numeric character that must be ignored and that all subsequent characters are numerals. Add 5 to the input value and print out the sum.

<em>Sample IO:</em>

Enter a string:

X123

The value +5 is:

128

<h2>Question 3</h2>

Using the previous 2 questions, write a program (<strong>question3.asm) </strong>to compute a simple 1dimensional spreadsheet containing integers and integer formulae. First, input the spreadsheet source values from the console, then perform calculations as outlined below and finally output the computed spreadsheet.

A cell may contain either an integer value or a formula that is a reference to another cell.  Cells are numbered 0-4 from top to bottom and a reference is indicated by a “=” prefix followed by the cell number (e.g., =2). A reference can only be made to a previous cell, and the cell referred to may itself contain a formula.

<em>Sample IO:</em>

Enter a series of 5 formulae:

1

2

3

=1

=2

The values are:

1

2

3

2

3


