This is GIT readme file with basic info.

On Centos you can INSTALL git by typing: yum install git;

Authorization is necessary before using git. First of all, type:\
git config --global user.name "YourUserNAME"\
git config --global user.email "Your@mail.address"

CLONE repo you can via git clone <repo URL> command;

Basic git commands:\
git add - marks changes to be included in the next commit;\
git commit - saves a new commit object in the local Git repository;\
git push - used to publish new local commits on a remote server;\
git pull - used to download and integrate remote changes.


git branch - list branches;\
git branch newbranchname - create new branch;\
git branch -D branchename - delete branch;\
git checkout branchname - switch to branch;\
git merge branchname - merge branch;


echo "# new-project" >> README.md\
git init\
git add README.md\
git commit -m "first commit"\
git branch -M main\
git remote add origin git@github.com:ch1madan/new-project.git\
git push -u origin main
