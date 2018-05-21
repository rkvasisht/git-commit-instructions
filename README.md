#Navigation Terminal
**cd**-> Change directory
- cd ~ -> change directory to Home
**ls**-> display what is in current directory with short list
**l**-> display complete file information in directory
**pwd**-> print wording directory, there where the hell am I command. 
**open**_> command will open a file in default program or directory in finder

#File Manipulation
- **man** -> will pull up manual for commands - q to exit
**>** -> redirects output to a File
**|** -> pipe will execute comman n left first then execute command on right
-`[command here] | [second command here]` - does not work for every command
- `echo 'test to add' > [File name]`- output directed into file !!!Will overwrite whats in there. 
- `echo 'text to add' >> [File Name]`- Output addended into file
**mkdir** -> create new directory from current postion
**touch** -> create new file within current directory,
**mv** -> move files 
- `mv [current file name] [new file name]` -- will rename the file
- `mv [current file name] ./newdirectory/[new file name]` -- will move the file and rename. Must exist. period in directory 
**rm** -> removes files or directories --!!! scary cannot undo
- `rm [file name]` -- removes file from system
- `rm -r [directory name]` -- removes directory and all subsequent files
- **grep** -> will search through documents for strings
-`cat [file name] | grep 'string to search'`-- will search contesnt of file and return 
-`-n` -- will display line number of found string
-`-A [number here]` -- will display trailing number of lines specifiec
-`B [Number here]-- will display preceding number of lines specified

#Git Commands
**git init** -> this will add a local git repository to a directory
**git status** -> this will show file that are untracked or tracked for the next commit
**git add** -> will add files to staging for next commit
-`git add [file name]` - will add individual file to staging
-`git add .` -same above
**git commit** -> takes staged files and creates save point / commit number
-`git commit -m 'enter in MEANINGFUL commit message'`
**git log** -> shows full log of all commits to master branch 
**git checkout** -> creates a new branch 
-`git checkout -b [branch name]` -creates a new branch and switches to that branch
-'git checkout [branch name]`'