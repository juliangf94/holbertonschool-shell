0-alias	Creates the alias ls to execute rm -f *. Must be executed with source or . to apply the alias to the current shell.
1-hello_you	Prints hello user using the environment variable $USER to get the current user's name.
2-path	Appends the directory /action to the end of the $PATH environment variable, making it the last location the shell searches for executables.
3-paths	Counts the number of directories listed in the $PATH variable using the echo, tr (to replace : with \n), and wc -l commands.
4-global_variables	Lists all environment variables (global) configured in the current shell using the printenv command.
5-local_variables	Lists all variables (local and global), functions, and shell options defined in the current environment using the set command.
6-create_local_variable	Creates a new local variable named BEST with the value "School".
7-create_global_variable	Creates a new environment variable (global) named BEST with the value "School", using the export command.
8-true_knowledge	Performs the addition of 128 with the value stored in the $TRUEKNOWLEDGE variable using arithmetic expansion ($((...))).
9-divide_and_rule	Performs integer division of $POWER by $DIVIDE using Bash arithmetic expansion.
10-love_exponent_breath	Calculates the power of $BREATH raised to $LOVE using the exponent operator ** inside arithmetic expansion.
11-binary_to_decimal	Converts a base 2 number (stored in $BINARY) to base 10 using base notation ($((2#$BINARY))).
12-combinations	Generates and prints all combinations of two lowercase letters (a to z), excluding the combination oo using grep -v.
13-print_float	Prints the value of $NUM with exactly two decimal places, using the printf command with the format specifier %.2f.
14-decimal_to_hexadecimal	Converts the decimal value in $DECIMAL to its hexadecimal representation, using the printf command with the format specifier %x.
