## Name: Douglas Doniel
## File: cssbs-hw06-Doniel
## Date: January 27,2021




***1. What is an exception?***
signal that an error has occurred cause the program to terminate
***2. What happens in a try block if the program executes without errors?***
If there are no errors than the block is runs to completion
***3. How does the catch mechanism work for unhandled exceptions?***
 Throws the exception,to the enclosing block
***4. What happens in a program if an exception block fails to handle an particular error?***
 the method immediately exits and execution returns to the calling method
***5. What is the parent class for all exceptions? How does this work?***
Exceptions class, all exceptions inherit from it
***6. How do you determine the type of an error?***
by putting the most specific exception at the top of the block
***7. What is the purpose of integer checking?***
always throws an OverflowException if an integer calculation in the block overflows
***8. What is the range of values that a signed Int32 type can contain? State the lowest value and the highest value.***
-2.147B-2.147B maxvalue and minvalue
***9. What is the range of values than an unsigned Int32 type can contain? State the lowest value and the highest value. What is the difference between a signed integer and an unsigned integer? Can signed integers and unsigned integers represent the same amount of numbers?***
0-4.294B Unsigned 
***10. What does the finally block do?***
 It ensures that a statement is always run, whether or not an exception has been thrown, 
***11. (Thought question) When would you not use a finally block in a try/catch construction?***
if you don't need to display a message or if you need to do resource managing