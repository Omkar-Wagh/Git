1).git status 

2).git init 
initialize the empty git repository

3).git init -b main
by default will have the git as master branch but we want to make it as main

4).git add readme.txt
adding files to the project
this file is added in the stagging environment

git add .
add all files to the stagging environment

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

10).git rm --cached credentials.txt
removes the file from the remote repository and then 
we can remove it from the local working directory 

11).git push -u origin main
pushes the code to  the remote repository
but before that we need to to ahve access rights for the e,ote repository

12).git push origin main
addling the updates that will reflect to the main origin 

git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main
if commiting for the first time

13).ssh-keygen -o
used to generate SSH key pairs with enhanced security

14).git tag -a v1.0 -m "version 1.0"
represents the versions of made each time 
add -> commit -> push 

15).git push origin v1.0
update the tags on remote repo 

