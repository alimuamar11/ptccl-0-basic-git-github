# ptccl-0-basic-git-github


git config
Usage: git config –global user.name “[name]”
Usage: git config –global user.email “[email address]”

git status
-> dalam workdir kemudian git add * =>dalam brance master

git reset * => unstage dari yang barusan di add, maka balik lagi ke workdir

git branch amir

git checkout amir 

Tutorial basic tentang Git dan Github

# basic git command

- git init
- git remote add origin https://github.com/myRepo/myRepository.git
 - git config --global user.email "ur.mail@dontknow.com"
 - git config --global user.name "ur.userName"
 - git add -A (all, of the file in the containing folder are add to the remote origin)
 - git commit -m (messages)
 - git push origin master
 
 
# a simplest way to perform pull request
- fork your target repo
-  add remote to the forking repo
- clone or pull to ur local machine
- start editing and add the changes
- push to master or branch
-  then click new pull request from github website, adding a few comment and create pull request

# Membuat Repository
-----------------------
## Langkah - langkah

1.Pertama login di situs Github dengan username dan password anda, kemudian klik Create New Repository.

2.Ketikan ``git clone https://github.com/alimuamar11/ptccl-0-basic-git-github.git``.

3.Lakukan edit pada readmi.md kemudian ketikan perintah ``git commit -m "Edit readme.md"``.

4.git push add origin master.

Tutorial lengkap https://www.petanikode.com/git-untuk-pemula/
