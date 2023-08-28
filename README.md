# GIT
Configuring GIT
<bir>
// "~" This symbol means we are under the root directory 
git config --global user.name "My name" //your account git hub name
gir config --global user.email "someone@email.com"
git config --list  //"what we setup in git config"

//Basic commands

Clone & Status

Clone- Cloning a repository on our local machine
**creating duplicate - copy the command from remote to local using the below command

git clone <- some Link ->

Status - display the state of the code

git status

//
use git status there are 4 types of status 
- Untracked = new files that git doesn't yet track.
- modified = changed
- staged = file is ready to be committed
- unmodified = unchanged
\\

//cd - change directory 
//ls- to check how many files
//ls -a  - to check hidden files


//
add & commit

add- adds new or changed files in your working directory to the git staging area.

git add "file name"
//git add .   - to add all files



commit - it is the record of change

git commit -m 'some message"

//command means- "Your branch is ahead of 'origin/main' by 1 commit."
The local system is ahead of the global system


Push command 

Push- upload local repo content to remote repo

 git push origin main
 











