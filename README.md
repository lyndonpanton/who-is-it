# who-is-it
Marked Programming Assignment 1 of the "Intermediate Object-Oriented Programming for Unity Games" course of the "C# Programming for Unity Game Development" Specialization by the University of Colorado via Coursera

## Description

For this assignment, you need to implement a PersonalDataPersonalData class as shown in the class diagram below:

The Visual Studio project I provided to you contains the PersonalDataPersonalData class (with the constructor and properties unimplemented) and a ProgramProgram class that tests the PersonalDataPersonalData class. You shouldn't change the Program.cs file at all (if you do, you'll break the automated grader), all your work in this assignment is in the PersonalData.cs file.

The class diagram above (and the code I provided) doesn't include the fields you'll need to include in the PersonalDataPersonalData class; figuring those out on your own is part of the assignment. Note that the only method is the constructor, which has a parameter for the name of the file that contains the data you need to use to populate the fields.

The input file contains a single csv string containing the data you'll store in your PersonalData object. The format of that string is:

<first name>,<middle name>,<last name>,<street address>,<city>,<state>,<postal code>,<country>,<phone number>

Take a look at the ValidData.txt file included in the materials zip file to see what it looks like with "real" data.

The best approach is to implement the constructor and the FirstNameFirstName property first (to pass test case 2), then implement the MiddleNameMiddleName property (to pass test case 3), and so on. Make sure you initialize all your fields to "" to ensure they have appropriate default values in the case of an invalid file name from the user (as Test Case 1 is testing).

Required Output Format

The Program.cs file I provided handles all the output correctly. It simply prints Passed or FAILED for each test case that's selected by the user input.

Running Your Code

Because of the code I included to work with the automated grader on Coursera, when you run your program the command prompt window will open and it will sit there doing nothing. To make your code run, type in a test case number (1 through 10, inclusive), a comma, and a file name and press the <Enter> key; your code should then run so you can check your output. 

For example, your input could be

3,ValidData.txt3,ValidData.txt

to run the third test case.

You can actually run your code again if you want to by typing in a test case number, a comma, and a file name and pressing the <Enter> key again. When you’re ready to stop running your code, type q (for quit).
    
## Getting Started

n/a

### Dependencies

* Windows 10
* Microsoft Visual Studio
* .NET

### Installing

* Download link: [Github Repository](https://github.com/lyndonpanton/who-is-it)

### Executing program

1. Go to the project's root directory
2. Go to the _ProgrammingAssignment1_ folder
3. Open _ProgrammingAssignment1.sln_ in Microsoft Visual Studio
4. Run _Program.cs_

## Help

n/a

## Authors

Lyndon Mykal Panton
[lyndonpanton](https://github.com/lyndonpanton/)

## Version History

* 0.1
    * Initial Release

## License

n/a

## Acknowledgments

Problem provided by the _University of Colorado_ and _Coursera_
