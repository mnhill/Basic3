
Firstly, to learn the basic things about the git hub repository download the git 
link: https://git-scm.com/download/win
when u visit this site download will be automatically generated.

Then, create a folder in your desktop like "basic"
and open this folder in 'Git Bash Here'.
now you are able to learn git cli.

type:
 git --version > it shows ur git version
 git init    > it shows the git repository in ur current folder means "Basic3"[if not any it shows - 
cli:
---
mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic3
$ git init
---

Initialized empty Git repository in C:/Users/mdala/Desktop/Basic/.git/
]

git status > it shows about branch master, no of commits, tracked and untracked files info.

now let's create a file in basic folder:

just using touch like ubuntu(debian)

touch basic.txt > it creates a basic.txt file in that folder.
To check about this folder just type
git status > it shows the file info. in that folder (basic)
cli:
--
mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic3 (master)
$ touch basic.md

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        basic.md

nothing added to commit but untracked files present (use "git add" to track)
---
now to push this in the git hub do things things:

type : git add . > it add all the files in that folder to track ( to push/commit)
[if u want to do for a specific file then type that file name like :
 git add basic.html  ( here basic.html is a file )]

now for commit first type:
git commit -am 'Basic3'  [ basic3 is the folder name]

now create a repository in a github file name as the folder name like 'Basic3'

now copy the git remote add origin line and past it on cli, after that u copy the git push line ( the last line ) and past it in cli and u need to sign up ur account with ur username  and password 
and  
then it will atomatically added to ur github account.
---
mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic3 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   basic.md
        


mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic3 (master)
$ git  add .

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic3 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   basic.md
        


mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic2 (master)
$ git commit -am 'Basic3'
[master (root-commit) 6b192db] Basic2
 2 files changed, 54 insertions(+)
 create mode 100644 basic.md
 

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic3 (master)
$ git remote add origin https://github.com/mnhill/Basic3.git

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic2 (master)
$ git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1008 bytes | 336.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/mnhill/Basic3.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/Basic3 (master)

---

overall CLI ARE GIVEN: 

---

---