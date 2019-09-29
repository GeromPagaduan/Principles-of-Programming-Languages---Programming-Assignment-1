# Principles-of-Programming-Languages---Programming-Assignment-1
Contains source files used for testing.
Contains a table for the grammar as a .csv file to perform shift and reduce operations properly.
Contains a lexical analyzer, a syntax analyzer, and a bottom-up parse tree.

# Programming_Assignment.py
Contains and uses the following (in this order):
- Lexical Analyzer
- Prints Grammar
- Syntax Analyzer
- Prints Parse Tree

# slr_table1.csv
This is the table used to perform shift and reduce operations. It passes on an action to a stack (such as s7), and goes to that state. It then goes to the column of what it's reading on the input string, which generates another action. This repeats until it hits $, signifying the end of file.

# source1.pas - source15.pas
This contains test files that were provided in class. The following errors should be detected for each one:

source1.pas -> Success!
source2.pas -> Success!
source3.pas -> Success!
source4.pas -> Error 07: identifier expected
source5.pas -> Error 08: special word missing
source6.pas -> Error 99: syntax error
source7.pas -> Error 09: symbol missing
source8.pas -> Error 10: data type expected
source9.pas -> Error 99: syntax error
source10.pas -> Error 09: symbol missing
source11.pas -> Error 09: symbol missing
source12.pas -> Error 11: identifier or literal value expected
source13.pas -> Error 99: syntax error
source14.pas -> Error 99: syntax error
source15.pas -> Error 06: EOF expected
