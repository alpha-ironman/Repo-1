# Repo Info Page
This is the first repository
By default The README.md will take the Repository name, and You can Change it.    


Untracked -> New files that git doesn't yet track  
Modified -> Something got changed in the file  
Staged -> File is in Staging area and can be move it to Local Branch  
Unmofified -> Nothing got chnaged in the file  

Use **git clone <link>** to get the copy of the project into the workarea  


**add** - Adds new or chnaged files in working area to the git staging area -> *git add filename*  
**commit** - It is the record of change -> *git commit -m 'some message'*  
**push** - Upload local repo content to remote Repo -> *git push origin main*  

  
*git init* - The git init command is used to create a new Git repository locally. When you run this command, Git sets up the necessary structures and files in the current directory, allowing you to start tracking changes.  

*git remote add origin "link"* - This is used to connect your local repository to a remote repository. and origin word is used as a alias for the link, you can replace that word with anything there!  

*git remote -v* - This is used to display the URLs of the remote repositories that are linked to local repository, here -v stands for "Verbose", Which means it provides detailed information  

*git branch* - This will lists all the local branches in the repository, The current branch us highlighted with an asterisk (*)  

*git branch 'name'* - create the branch locally with specified name  

*git branch -d 'name'* - Delete the specified branch locally  

*git branch -m 'new-name'* - Rename with new-name locally  

*git branch -r* - Lists all the branches from the remote Repository  

*git push origin main* - This will push the code from local branch to remote branch, here origin is remote repo name and Main is branch name  

*git push -u origin main* - This will set the default path as origin main, so from next time you can simply go like: git push  



*git checkout -b 'new branch name'* - To create new Branch  

*git checkout 'branch name'* - To navigate  

*git branch -d 'branch name' -  to delete branch  

*git diff 'branch name* - to compare, branches, files & More  

*git merge 'branch name* -  to merge 2 branches with **Fast-forward Commit**  

*git merge --no-ff 'branch_name'* - to merge branches with **merge commit**

*git reset 'file name'* -  This is used to get back to the file to the workspace from stagged area  

*git reset HEAD~1* -  This is for commited changes  

*git reset 'commit hash'* - This is for multiple commits  

*git hash-object _finalname_* - This will give the Hash/ Object Id of the File  

*git log* - This will give the commit history with most recent on the top  

*git show _id_* -  This will show the details about the provided hash id  

*git tag* - Show all the tags  

*git tag _tag_name_ _commit-value_* -  This will tag the commit value provided, If not defaults to HEAD #used to create lightweight tag  

*git tag -a -m _msg_ / -f _file_ _tagname_ commitvalue* -  This will tag the commnit with message or the file attached to it and that file contains message about that commit, if commit value is not provided then defaults to HEAD  


#Interactive Commands

p, Pick = Use Commit  
r, Reword =  Use Commit, but edit the commit message  
e, edit = Use commit, but stop for amending  
s, squash = Use commit, but meld into previous commit  
f, fixup = like "squash", but discard this commit's log message  
x, exec =  run command using shell  
d, drop = remove commit  


![image](https://github.com/user-attachments/assets/fd6ded77-f0e1-4954-9d34-4762f43ac1bb)
