# Lesson 5 SUMMARY

1.  **:!command**  executes an external command.
Some useful examples are:
 - :!dir(MS-DOS)            :!ls(Unix) -  shows a directory listing.
 - :!del FILENAME(MS-DOS)   :!rm FILENAME(Unix) -  removes file FILENAME.

2.  **:w FILENAME**  writes the current Vim file to disk with name FILENAME.

3.  **v  motion  :w FILENAME**  saves the Visually selected lines in file FILENAME.

4.  **:r FILENAME**  retrieves disk file FILENAME and puts it below the cursor position.

5.  **:r !dir**  reads the output of the dir command and puts it below the cursor position.

