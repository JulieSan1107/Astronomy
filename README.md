Wenyin San
February 17, 2015
CSCI_4430 Prolang
Assignment 1

Information: These are the 3 parts for Assignment_1. This assignment is done individually.

Files associated: puzzle.pl, parse.pl, db.pl, README

Part 1: Run swipl.
        Type "[puzzle]." to compile the program.
        Type "puzzle(Solution).", and receive 4 valid solutions to the puzzle:
        
Part 2: Run swipl.
        Type "[parse]." to compile the program.
        Type "loop." to continuously input sentences and receive the resulting parse tree.
 (Extra)Type "loop." to continuously input parse tree, and receive the sentence formed from the tree.
 
Part 3: Run swipl.
        Type "[db]." to compile the program.
        Enter either a command or a query.
        The query output either a 'yes' or a 'no' depending on whether the statement is true or false.
        Example:
               ?- loop.
               |: the person john left.
               |: the person jane left.
               |: did a person leave?
               yes
               |: did every person leave?
               yes
               |: the person jake did not leave.
               |: did a person leave?
               yes
               |: did every person leave?
               no
               |: did a train arrive?
               no
               |: did every train arrive?
               yes

