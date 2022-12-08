# Boom!
HOW IT WORKS

Prompt to the user (’$’), representing that it is ready to accept
user  input.   After it reads the arguments and executes the com‐
mands in order which are provided by the user.

Order of execution of command ‐

User input will split into tokens, these tokens will be  compared
to  builtin  command,  if  it  matches  then  it will execute the
builtin command. Then user returns to prompt. If the match is not
found  in  builtin  command, then tokens will be compared to exe‐
cutables in PATH or in PWD.  If the match is found in excutables,
then execute the command and user return to the prompt.

If  the  match is not found in both  builtin command and executa‐
bles in PATH or PWD, then it prints Error Message and user return
to the prompt.

Builtin Commands

cd ‐ Changes the current working directory Ex ‐ cd xyz

env ‐ Prints environmental variables Ex ‐ env

exit ‐ Exits the shell Ex ‐ exit

AUTHORS Pallivi Jagtap, Matt Buckingham and Wendy Wu
