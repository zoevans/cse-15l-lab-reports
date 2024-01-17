cd
1) no arguments

![Image](cd_no_argument.png)

When cd is followed by no arguments, nothing is printed, and the terminal takes you back to the highest level directory. In this example, I was in the messages directory, and after the cd command, in the next line, the terminal started back at the home directory, which is the outermost directory. I got this output because I tried to change directories, without providing a specific directory that was possible to change to as an argument. So, this means that if no argument is provided after cd, the cd command will take you back to the highest level directory. The output was not an error and no error message was printed.
   
2) path to directory as an argument
   
![Image](cd_directory.png)

When cd is followed by a path to a directory as an argument, nothing is printed, and the next line in the terminal takes you into that directory that was used as an argument. In this example, I was in the lecture1 directory to start, and after the cd command with the directory argument, I was put into the messages directory in the next line. I got this output because I used the messages directory as my argument after cd, so the cd command changed the directory of the next line of the terminal to the messages directory. This means that if cd is followed by a path to a directory as an argument, it will take you to that directory in the next line of the terminal, as long as that nested directory is actually accessible from your current directory. The output was not an error, as no error messages were printed, and the code successfully took me to a nested directory.
  
3) path to a file as an argument

![Image](cd_file.png)

When cd is followed by a path to a file as an argument, you stay in the same directory, but you recieve an error message stating that the action isn't possible because the file isn't a possible directory to switch to. In this example, I was in the messages directory, and after the command was run, I still remained in the same directory, and the terminal printed an error that stated the file was not a valid argument because it was "Not a directory." This means that you can only include a directory as an argument after cd, not a path to a file. The output was definitely an error because the cd command failed to take me to a different directory and the terminal stated that the argument inputted was not valid because it was not a directory.

ls
1) no arguments


   
When ls is followed by no arguments, you stay in the same directory, but the terminal prints the different potential directories that you can move to that are contained within the current directory that you are in. In this example, I was in the messages directory, and after the command was run, I stayed in the same directory, and the terminal printed the subdirectories contained within the messages directory that I could move to. This means that when you don't include an argument after the ls command, the terminal will print the names of the different directories that you could possibly switch to while you're in your current directory. The output was not an error because the terminal printed useful information about which directories I was able to move to.

2) path to a directory as an argument

When ls is followed by a path to a directory as an argument, you stay in the same directory and the terminal prints the different subdirectories contained within the directory that was used as an argument. For example, I was in the highest directory, and after the command was run, I stayed in the same directory, and the terminal printed the subdirectories contained within the lectures directory, which was the same directory that I used as the argument. This means that when you use a path to a directory as an argument after the ls command, you will stay in the same directory, and the terminal will print the list of subdirectories contained within the directory that you used as an argument. The output was not an error because the terminal printed useful information about what subdirectories were contained in the directory that I used as an argument.

3) path to a file as an argument

When ls is followed by a path to a file as an argument, you stay in the same directory, and the terminal prints out an error, stating that the action isn't possible because the argument was not a valid directory. In this example, I was in the lectures directory, and after the command was run, I stayed in the same directory, and the terminal printed an error message, stating that the file used as an argument was not a valid argument because it was "Not a directory." This means that you can only include a directory as an argument after ls, not a path to a file. The output was obviously an error because the ls command failed to complete any action and the terminal verified that the argument inputted was not valid because it was not a directory.

cat
1) no arguments

When cat is followed by no arguments, you are given the option to type in text, and the terminal will print 2 lines of whatever text you inputted before pressing enter. For example, I was in the lecture directory, and after the command was run with no arguments, I was taken to the next line and typed in the text "hello world" and pressed enter. As a result, the terminal printed a duplicate of the line, leaving two printed lines of the text "hello world." This means that if you include no arguments after the cat command, the terminal will print 2 lines of whatever text you enter into the prompted terminal line. The output was not an error because the terminal performed an action without an error message.  

2) path to a directory as an argument

When cat is followed by a path to a directory as an argument, you stay in the same directory, and the terminal prints an error message, stating that the argument provided is a directory. In this example, I was in the lecture directory, and after the command was run, I stayed in the same directory, and the terminal printed an error message, stating that the argument used "Is a directory" and no futher action was taken. This means that if you include a directory as an argument after the cat command, the terminal will keep you in the same directory and provide you with an error message prompting you to choose something other than a directory as an argument. Therefore, the output was definitely an error because there was an error message and the terminal performed no action.

3) path to a file as an argument

When cat was followed by a path to a file as an argument, you stay in the same directory, and the terminal prints all of the text included in the file that was used as the argument. In this example, I was in the lecture directory, and after the command was run, I stayed in the same directory, and the terminal printed all of the text that was included in the Hello.java file, which was the file that I used as the argument. This means that if you use a path to a file as an argument for a cat command, it will print the text contents of whatever file is inputted as the argument. The output was not an error as the terminal did not provide an error message and an action was executed. 
