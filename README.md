
deell@deell-PC MINGW64 ~/Desktop/myGitApp
$ git index.html
git: 'index.html' is not a git command. See 'git --help'.

deell@deell-PC MINGW64 ~/Desktop/myGitApp
$ touch index.html

deell@deell-PC MINGW64 ~/Desktop/myGitApp
$ touch app.js

deell@deell-PC MINGW64 ~/Desktop/myGitApp
$ git init
Initialized empty Git repository in C:/Users/deell/Desktop/myGitApp/.git/

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git config --global user.name 'raviprakash23'

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git config --global user.email 'raviprakash23@gmail.com'

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git add index.html

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git rm --cached index.html
rm 'index.html'

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js
        index.html

nothing added to commit but untracked files present (use "git add" to track)

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git add *.html

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git rm --cached index.html
rm 'index.html'

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js
        index.html

nothing added to commit but untracked files present (use "git add" to track)

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git add .

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   index.html


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git add .

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git commit
Aborting commit due to empty commit message.

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   app.js


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git add .

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git commit -m 'Changed in app.js'
[master (root-commit) 98cff38] Changed in app.js
 2 files changed, 126 insertions(+)
 create mode 100644 app.js
 create mode 100644 index.html

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ touch -gitinore
touch: unknown option -- g
Try 'touch --help' for more information.

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ rouch .gitignore
bash: rouch: command not found

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ touch .gitignore

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ touch log.txt

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git add .

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git add .

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git staus
git: 'staus' is not a git command. See 'git --help'.

The most similar command is
        status

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore
        new file:   dev1/app1.js
        new file:   dev2/app2.js


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git login
git: 'login' is not a git command. See 'git --help'.

The most similar command is
        column

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git branch login

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore
        new file:   dev1/app1.js
        new file:   dev2/app2.js


deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git commit -m 'another change'
[master 104aecc] another change
 3 files changed, 3 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 dev1/app1.js
 create mode 100644 dev2/app2.js

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git checkout login
Switched to branch 'login'

deell@deell-PC MINGW64 ~/Desktop/myGitApp (login)
$ touch login.html

deell@deell-PC MINGW64 ~/Desktop/myGitApp (login)
$ git add .

deell@deell-PC MINGW64 ~/Desktop/myGitApp (login)
$ git commit -m 'login form'
[login a2bafc8] login form
 3 files changed, 34 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 login.html

deell@deell-PC MINGW64 ~/Desktop/myGitApp (login)
$ git checkout master
Switched to branch 'master'

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git merge login
Merge made by the 'recursive' strategy.
 index.html |  2 +-
 login.html | 32 ++++++++++++++++++++++++++++++++
 2 files changed, 33 insertions(+), 1 deletion(-)
 create mode 100644 login.html

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git remote

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git remote add origin https://github.com/RaviPrakash23/myAppSample.git

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git remote
origin

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ git push -u origin master
Counting objects: 16, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (11/11), done.
Writing objects: 100% (16/16), 3.26 KiB | 0 bytes/s, done.
Total 16 (delta 4), reused 0 (delta 0)
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/RaviPrakash23/myAppSample.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$ touch README.md

deell@deell-PC MINGW64 ~/Desktop/myGitApp (master)
$
