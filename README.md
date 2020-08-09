# Sample Project for learning git
first make directory for php project and run `git init` command
then folder **_`.git`_** creat in root dir.
I practice below commands,
for initial git
> git init

after run this command, all files, directories and subdirectories, are tracked.
then creat project files such as index.html
> git status

show that we still not add any file in stash or stage
run this command until files `added` in `stage`
example:
> git add index.html

now our files are cached in stage and we can `versioning` it.
with `commit` argument for **_git_** command do it.
> git commit -m "add index.html to local repository (.git)"
