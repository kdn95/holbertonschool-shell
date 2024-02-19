Shell, init files, variables and expansions
# 0-alias = alias ls='rm *' (Create a script that creates an alias. Name: ls Value: rm *) \n
# 1-hello_you = echo 'hello $USER' ( a script that prints hello user, where user is the current Linux user) \n
# 2-path = PATH="$PATH:/action" (Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.) \n
# 3-paths = echo $PATH | tr ":" "\n" | grep / | wc -l (a script that counts the number of directories in the PATH) \n
# 4-global_variables = printenv (a script that lists environment variables) \n
# 5-local_variables = set (a script that lists all local variables and environment variables, and functions) \n
# 6-create_local_variable = export local BEST='School' (a script that creates a new local variable. Name: BEST Value: School) \n
# 7-create_global_variable = export BEST='School' (a script that creates a new global variable) \n
# 8-true_knowledge = echo $(($TRUEKNOWLEDGE+128)) ( a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line) \n
# 9-divide_and_rule = echo $((POWER/DIVIDE)) (a script that prints the result of POWER divided by DIVIDE, followed by a new line. POWER and DIVIDE are environment variables) \n
# 10-love_exponent_breath = echo $((BREATH**LOVE)) (a script that displays the result of BREATH to the power LOVE. BREATH and LOVE are environment variables. The script should display the result, followed by a new line) \n
# 11-binary_to_decimal = echo $((2#$BINARY)) (Write a script that converts a number from base 2 to base 10. The number in base 2 is stored in the environment variable BINARY. The script should display the number in base 10, followed by a new line) \n
# 12-combinations = echo {a..z}{a..z} | tr [[:blank:]] '\n' | grep -v 'oo' (Create a script that prints all possible combinations of two letters, except oo. Letters are lower cases, from a to z. One combination per line. The output should be alpha ordered, starting with aa. Do not print oo. Your script file should contain maximum 64 characters) \n
# 13-print_float = printf "%.2fn" "$NUM" (a script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM.) \n
# 14-decimal_to_hexadecimal = printf "%x\n" $DECIMAL ( a script that converts a number from base 10 to base 16. The number in base 10 is stored in the environment variable DECIMAL. The script should display the number in base 16, followed by a new line) \n
#NOTE FROM PROJECT = 'Read your /etc/profile, /etc/inputrc, ~/.bashrc files'
