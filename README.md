# Sample Project for learning git
### I use https://www.markdownguide.org/basic-syntax/ location for write this script.  
first make directory for php project and run `git init` command.  
then folder **_`.git`_** creat in root dir.
I practice below commands;
for initial git
> git init

after `git init` we can introduce ourself to git.  
> git config --global user.name "Shervin"  
> git config --global user.email "shervin.hz07@gmail.com"

after run this commands, all files, directories and subdirectories, are tracked.  
then create project files such as index.html
> git status

`git status` show that we still not add any file in stash or stage.    
run this command until files `added` in `stage`
example:
> git add index.html

now our files are cached in stage and we can `versioning` it.  
with `commit` argument for **git** command do it.  
> git commit -m "add index.html to local repository (.git)"

switch `-m` for above command is the _message_ that usually begins with a verb
and describes about last commit.  
until now we have one version of our project.  
> git log

show commits with related hash.   
if we have many commits, _`it can seen in one line for each commit`_,  
we can transfer between them by using below command,  
> git checkout _related-hash_    
> git log --oneline  

too instead of two command `git add` and `git commit`,  
we can use one command in below.  
> git commit -a -m "changed index.html at Aug 9"  

-a -> automatically add.  
note that use once from command `git status`. not required a lot.  
all changes in local repo. for send my project in remote repository explain in below,  
be carfule that before anything it used `git commit`,  
we must add a remote repo to our git.  
> git remote add origin https://github.com/shervin-h/my-first-repo  
> git push -u origin master  

origin is main remote repository. itself word origin can be any name.  
switch -u is optional and master is branch that we work.  
now we connected to remote repo.

 
