cd
1) no arguments

![Image](cd_no_argument.png)

When cd is followed by no arguments, nothing is printed, and the terminal takes you back to the highest level directory. In this example, I was in the messages directory, and after the cd command, in the next line, the terminal started back at the home directory, which is the outermost directory. I got this output because I tried to change directories, without providing a specific directory that was possible to change to as an argument. So, this means that if no argument is provided after cd, the cd command will take you back to the highest level directory. The output was not an error and no error message was printed.
   
2) path to directory as an argument
![Image](cd_directory.png)

When cd is followed by a path to a directory as an argument, nothing is printed, and the next line in the terminal takes you into that directory that was used as an argument. In this example, I was in the lecture1 directory to start, and after the cd command with the directory argument, I was put into the messages directory in the next line. I got this output because I used the messages directory as my argument after cd, so the cd command changed the directory of the next line of the terminal to the messages directory. This means that if cd is followed by a path to a directory as an argument, it will take you to that directory in the next line of the terminal, as long as that nested directory is actually accessible from your current directory. The output was not an error, as no error messages were printed, and the code successfully took me to a nested directory.
  
3) path to a file as an argument
![Image](cd_file.png)

When cd is followed by a path to a file as an argument, you stay in the same directory, but you recieve an error message stating that the action isn't possible because the file isn't a possible directory to switch to. In this example, I was in the messages directory, and after the command was run, I still remained in the same directory, and "

ls
1) no arguments
2) path to a directory as an argument
3) path to a file as an argument

cat
1) no arguments
2) path to a directory as an argument
3) path to a file as an argument
