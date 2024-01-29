# Git-Tutorials
What is Git?
Version control system is a tools that helps to track changes in code.
1. Track the history
2. Collaborate

What is github?
Website that allows developers to stor eand manage their code using git.

Explain the basic git commands.
git --version // Check the git version
<br>
ls/ls -a // check list of file
<br>
git config --global user.name // check the git user name
<br>
git config --global user.name "Sandeep"// set the git user name
<br>
git config --global user.email // set the git user 
<br>
git config --global user.email "Sandeep@email.com"// set the git user email
<br>
git config -- list // Check the setting or status of name /email /etc.
<br>
git clone (github link) // clone the github repository on our local machine.
<br>
cd / cd .. // change directory
<br>
git status -- 1. untrached // new file that git doesn't yet track.
<br>
2. modified  // changed file 
<br>
3. staged  // file is ready to be committed.
<br>
4. unmodified  // unchanged
<br>
git add (file name) / git add . // adds new or changed files in your working directory to the git staging area.
<br>
git commit -m "add all changed file" // it is the record of change.
<br>
git push origin main // upload local repo content to remote repo. // remote -- github // local -- laptop/pc. // main -- is branch // origin -- is name 
<br>
git push -u  origin main // after this u can use git push only this is also working. // -u -- set upstream.
<br>
2nd Method to insert the code.
<br>
git init // used to create a new git repo
<br>
mkdir (folder name)  // create new repo using  vs code /compiler ide.
<br>
git remote add origin (github link) // add github link
<br>
git remote -v // to verfiy remote.
<br>
git branch // to check branch
<br>
git branch -M main // to rename branch // main-- in place u can give your new branch name.
<br>

# Branch Commands
<br>
git checkout (branch name)  // to navigate 
<br>
git checkout -b (new branch name) // to create new branch
<br>
git checkout -d (branch name)  // to delete branch
<br>

# Merging Code
<br>
git diff (branch name) // to compare commits, branches, files and more.
<br>
git merge (branch name)  // to merge 2 branches.
<br>

# Pull Command / Create Pull

<br>
Create a  pull request // it lets you tell others about changes you've pushed to a branch in a repository on github.
<br>
git pull origin main  // used to fetch and download content from a remote repo and immediately update the local repo to match that content.
<br>
Resolving merge conflicts -- //An event that takes place when git is unable to automatically reslove difference in code b/w two commits.
<br>



