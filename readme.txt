1).git status 

2).git init 
initialize the empty git repository

3).git init -b main
by default will have the git as master branch but we want to make it as main

4).git add readme.txt
adding files to the project
this file is added in the stagging environment

5).git rm --cached readme.txt
this command unstage the file from the git stagging environment 

6).git commit -m " first commit by omkar"
add the files to the remote repository with message 

7).git log 
represent the commit history with time Author

8).git commit -a -m "Another Commit Without Stagging Environment"
skips the stagging environment and commit to the main 

9).git diff
specifies the changes in the file location
git diff --staged
for the files which are at the stagging environment

10).