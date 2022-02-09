# 42 Get_Next_Line
This project is about programming a function that returns a line
read from a file descriptor.

## General Instructions
- Return the line that was read, and NULL if there is nothing else to read or an error occured.
- **Return the \n character except if EOF is reached**
- **Forbidden:**
  - Libft
  - `lseek()`
  - Global Variables
- Compile with flag, -D BUFFER_SIZE=XX
	`gcc -Wall -Werror -Wextra -D BUFFER_SIZE=XX *.c`
- Don't be an idiot like me, each time gnl is run, it returns only ***one*** line. Say you have 3 lines in 1 .txt file, you would have to run gnl 3 times to output all 3 lines.

## Valgrind
Lowkey saved my life.

- How to run Valgrind [here](https://stackoverflow.com/questions/5134891/how-do-i-use-valgrind-to-find-memory-leaks)
- Understanding [Valgrind's messages](https://epitech-2022-technical-documentation.readthedocs.io/en/latest/valgrind.html)

**A REMINDER TO REMOVE ALL COMMENTS WITHIN THE CODE BEFORE YOU SUBMIT THANKS**