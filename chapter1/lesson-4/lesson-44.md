# Lesson 4.4: THE SUBSTITUTE COMMAND

** Type  :s/old/new/g  to substitute 'new' for 'old'. **

1. Move the cursor to the line below marked --->.

2. Type  **:s/thee/the < ENTER >** .  Note that this command only changes the first occurrence of "thee" in the line.

3. Now type  **:s/thee/the/g** .  Adding the  **g**  flag means to substitute globally in the line, change all occurrences of "thee" in the line.
---> thee best time to see thee flowers is in thee spring.

4. To change every occurrence of a character string between two lines,
 - type   **:#,#s/old/new/g**    where #,# are the line numbers of the range of lines where the substitution is to be done.
 - Type   **:%s/old/new/g**      to change every occurrence in the whole file.
 - Type   **:%s/old/new/gc**     to find every occurrence in the whole file, with a prompt whether to substitute or not.

