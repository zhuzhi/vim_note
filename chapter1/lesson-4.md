# Lesson 4 SUMMARY

1. - **CTRL-G**  displays your location in the file and the file status.
 - **G**  moves to the end of the file.
 - **number  G**  moves to that line number.
 - **gg**  moves to the first line.

2. - Typing  **/**  followed by a phrase searches FORWARD for the phrase.
 - Typing  **?**  followed by a phrase searches BACKWARD for the phrase.
After a search type  **n**  to find the next occurrence in the same direction or  **N**  to search in the opposite direction.
 - **CTRL-O** takes you back to older positions, **CTRL-I** to newer positions.
 
3. Typing  **%**  while the cursor is on a (,),[,],{, or } goes to its match.

4. - To substitute new for the first old in a line type    **:s/old/new**
 - To substitute new for all 'old's on a line type       **:s/old/new/g**
 - To substitute phrases between two line #'s type       **:#,#s/old/new/g**
 - To substitute all occurrences in the file type       ** :%s/old/new/g**
 - To ask for confirmation each time add 'c'             **:%s/old/new/gc**
