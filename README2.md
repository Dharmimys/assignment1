1. What is merge conflict?
Ans.: Merge conflict is a error while merging the 2 repo.
conflict arises when 2 branchs have made edits in same line in a file,
or one file is edited by some line & another developer is edited the same line
and when try to merge it conflict occurs

2. How to identify the conflict?
Ans.: if a programm found the code writen like
the below example the conflicts occurs

" <<<<<<< HEAD
Line written by dev1 
=======
Line written by dev2
>>>>>>> "

The ======= line is the "center" of the conflict. 
All the content between the center and the 
<<<<<<< HEAD line is content that exists in the 
current branch main which the HEAD ref is pointing to. 
Alternatively all content between the center and >>>>>>> 
is content that is present in 
our merging branch.

3. How to resolve the conflict?
Ans.: to resolve a merge conflict is to edit the conflicted file.
open the txt file remove the conflict dividers "=======" , <<<<<< & >>>>>>>>
and keep which line best for the program and delete the other line if not required