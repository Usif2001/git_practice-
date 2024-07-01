Hello Git and GitHub
how I reached: 
35841@LAPTOP-J8APK280 MINGW64 ~
$ mkdir git_practice

35841@LAPTOP-J8APK280 MINGW64 ~
$ cd git_practice

35841@LAPTOP-J8APK280 MINGW64 ~/git_practice
$ git init
Initialized empty Git repository in C:/Users/35841/git_practice/.git/

35841@LAPTOP-J8APK280 MINGW64 ~/git_practice (master)
$ echo "Hello Git and GitHub" >> README.txt

35841@LAPTOP-J8APK280 MINGW64 ~/git_practice (master)
$ git add README.txt
warning: in the working copy of 'README.txt', LF will be replaced by CRLF the next time Git touches it

35841@LAPTOP-J8APK280 MINGW64 ~/git_practice (master)
$ git commit -m "First commit"
[master (root-commit) 598ffd1] First commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt

35841@LAPTOP-J8APK280 MINGW64 ~/git_practice (master)
$ git status
On branch master
nothing to commit, working tree clean

35841@LAPTOP-J8APK280 MINGW64 ~/git_practice (master)
$ git remote add origin https://github.com/Usif2001/git_practice-.git
git branch -M main
git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 234 bytes | 117.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Usif2001/git_practice-.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

35841@LAPTOP-J8APK280 MINGW64 ~/git_practice (main)
$
