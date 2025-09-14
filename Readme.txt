Kea Papas@LAPTOP-H175QIKR MINGW64 ~
$ mkdir PAPAS_IT120_Act1

Kea Papas@LAPTOP-H175QIKR MINGW64 ~
$ cd PAPAS_IT120_Act1

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1
$ touch Profile.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1
$ touch Education.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1
$ touch Background.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1
$ touch Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1
$ touch Test.py

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1
$ git init
Initialized empty Git repository in C:/Users/Kea Papas/PAPAS_IT120_Act1/.git/

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git add .
warning: in the working copy of 'Test.py', LF will be replaced by CRLF the next time Git touches it
Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Background.txt
        new file:   Education.txt
        new file:   Profile.txt
        new file:   Readme.txt
        new file:   Test.py


Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git commit -m "Initial commit - Added all base files"
[master (root-commit) 3a67e4e] Initial commit - Added all base files
 5 files changed, 14 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git status
On branch master
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git add .

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git commit -m "Add initial info to files"
On branch master
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git branch PAPAS_B1

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git branch PAPAS_B2

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git branch PAPAS_B3

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git branch PAPAS_B4

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git status
On branch master
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git branch
  PAPAS_B1
  PAPAS_B2
  PAPAS_B3
  PAPAS_B4
* master

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git checkout PAPAS_B1
Switched to branch 'PAPAS_B1'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B1)
$ git merge master
Already up to date.

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B1)
$ git add Profile.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B1)
$ git commit -m "added addtional details in Profile.txt"
[PAPAS_B1 7813c79] added addtional details in Profile.txt
 1 file changed, 7 insertions(+), 1 deletion(-)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B1)
$ git status
On branch PAPAS_B1
nothing to commit, working tree clean
