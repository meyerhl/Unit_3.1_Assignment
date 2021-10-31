# Unit_3.1_Assignment
Create Abstract Class

Please view the BibleData3 file for raw data.

Please view the AbstractBibleBook file for programming code.

Given the previously created collection of all Bible Books in the New Testament, create
an abstract class that serves as the base class for a series of subclasses for the
different categories of Books in the New Testament. You should update your tet file to
further distinguish into the correct categories and write programming logic to create
instances of the correct kinds of classes.

The class heirarchy should be:

Abstract Class: Bible Book 
> Gospel
> Abstract Class: Letter
>>>>>> Local Church Letter
>>>>>> Pastoral Epistles
>>>>>> General Epistles

There should be an abstract method at the BibleBook level called "display" that should
be implmented at a lower level to dictate the type of book along with its name and 
number of chapters.
