# DevOps-demo
Remote-Git repository creation
<br>
I'm going to clone this repository on local pc using git clone (url),
then i will create file in cloned repository and 
<br>
add that file in staging area of git using git add [file] command
<br> 
and then record what we have changed in file using git commit -m “[descriptive message]”
<br>
and finally we will going to update our remote repository using command git push origin main
<br>
<br>
Now,my second task is to merge two branch using pull request in Github and 'git pull origin main' command in Git
<br>
for that first i am going to create new branch using command 'git checkout -b [branch-name]'
<br>
Make changes in this newly created branch, before that check current working branch using command 'git branch',
<br>
If it isn't on newly created branch you can switch to another branch using comand 'git checkout [branch-name]'
<br>
 Note that changes that we have made is only going to record in branch that we have created before.
<br>
Now to update changes in remote repository in GitHub for new branch use command 'git push origin [branch-name]'
<br>
Now on github click on 'compare & pull request'  -> 'create pull request' -> 'merge pull request' -> 'Confirm merge'
<br>
To reflect merge changes from github remote repository to local repository,
<br>
We simply use command 'git pull origin main' but before that switch to main branch 