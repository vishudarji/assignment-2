# assignment-2
assignment of branches
admin@ADMIN MINGW64 ~
$ cd desktop

admin@ADMIN MINGW64 ~/desktop
$ mkdir Patronus

admin@ADMIN MINGW64 ~/desktop
$ cd Patronus

admin@ADMIN MINGW64 ~/desktop/Patronus
$ touch patronus.txt

admin@ADMIN MINGW64 ~/desktop/Patronus
$ git init
Initialized empty Git repository in C:/Users/admin/Desktop/Patronus/.git/

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git add .

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git commit -m ' add empty patronus file'
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'admin@ADMIN.(none)')

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git config -- user.email "vishwadarji2412@gmail.com"

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git config -- user.name "vishwa"

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git commit -m 'add empty patronus file'
[master (root-commit) 024d064] add empty patronus file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 patronus.txt

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git branch harry snape
fatal: not a valid object name: 'snape'

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git branch harry

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git branch snape

admin@ADMIN MINGW64 ~/desktop/Patronus (master)
$ git checkout harry
Switched to branch 'harry'

admin@ADMIN MINGW64 ~/desktop/Patronus (harry)
$ git checkout snape
Switched to branch 'snape'
M       patronus.txt

admin@ADMIN MINGW64 ~/desktop/Patronus (snape)
$ git branch lily

admin@ADMIN MINGW64 ~/desktop/Patronus (snape)
$ git checkout lily
Switched to branch 'lily'
M       patronus.txt

admin@ADMIN MINGW64 ~/desktop/Patronus (lily)
$ git add .

admin@ADMIN MINGW64 ~/desktop/Patronus (lily)
$ git commit -m 'add lilys doe patronus'
[lily eaab6e8] add lilys doe patronus
 1 file changed, 45 insertions(+)

admin@ADMIN MINGW64 ~/desktop/Patronus (lily)
$ git branch -a
  harry
* lily
  master
  snape

admin@ADMIN MINGW64 ~/desktop/Patronus (lily)
$
