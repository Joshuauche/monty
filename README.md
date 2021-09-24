#	The Monty Language
	Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.


##	Monty Byte Code Files
	Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:



#	The monty program
##	Compilation & Output
	You should compiled the files this way:
	
	$ gcc -Wall -Werror -Wextra -pedantic *.c -o monty
	
##	Usage:
	./monty file

	Where file is the path to the file containing Monty byte code. If the user does not give any file or more than one argument to your program, print the error message:


