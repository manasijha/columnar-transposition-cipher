# Columnar transposition cipher

In a columnar transposition, the message is written out in rows of a fixed length, and then read out again column by column, and the columns are chosen in some scrambled order. Both the width of the rows and the permutation of the columns are usually defined by a keyword.

For example, the keyword FLAGS is of length 5 (so the rows are of length 5), and the permutation is defined by the alphabetical order of the letters in the keyword. In this case, the order would be "2 4 1 3 5".
 
In a regular columnar transposition cipher, any spare spaces are filled with nulls; in an irregular columnar transposition cipher, the spaces are left blank.Finally, the message is read off in columns, in the order specified by the keyword.
 
For example, suppose we use the keyword FLAGS and the message HELLO LUCIFER.LETS MEET AT CAFE. In a regular columnar transposition, we write this into the grid as follows:
 
 
2 4 1 3 5
H E L L O
L U C I F
E R L E T
S M E E T
A T C A F
E

In the irregular case, the columns are not completed by nulls:

The cipher text comes out to be:

LCLECHLESAELIEEALCLECOFTTF

In a regular columnar transposition, we write this into the grid as follows:

2 4 1 3 5
H E L L O
L U C I F
E R L E T
S M E E T
A T C A F
E X X X X

The cipher text comes out to be:

LCLECXHLESAELIEEAXLCLECXOFTTFX



This project has a code to decrypt the columnar transposition cipher to text.

The code can be read from code.py
