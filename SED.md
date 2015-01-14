SED TIPS
========

Add a blank line at a given position[1]

	sed g 2 <filename>

add a blank line at line 2 of filename[2].
Instead of a number you can also use a regex delimited by the '/'
character.


<!--
References
----------
-->
[1]: http://www.thegeekstuff.com/2009/11/unix-sed-tutorial-append-insert-replace-and-count-file-lines/#insert_line 
"Unix Sed Tutorial - insert lines"
[2]: http://stackoverflow.com/questions/17363030/how-do-i-insert-a-newline-linebreak-after-a-line-using-sed "StackOverflow - blank lines"
