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

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B1)
$ git add Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B1)
$ git commit -m "Add commands to Readme.txt"
[PAPAS_B1 dce2721] Add commands to Readme.txt
 1 file changed, 111 insertions(+)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B1)
$ git checkout PAPAS_B2
Switched to branch 'PAPAS_B2'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B2)
$ git status
On branch PAPAS_B2
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B2)
$ git add Education.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B2)
$ git commit -m "Added College details in Education.txt"
[PAPAS_B2 bdafd40] Added College details in Education.txt
 1 file changed, 4 insertions(+), 1 deletion(-)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B2)
$ git checkout PAPAS_B1 -- Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B2)
$ git status
On branch PAPAS_B2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B2)
$ git add Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B2)
$ git commit -m "Insert commands to Readme.txt"
[PAPAS_B2 de6da40] Insert commands to Readme.txt
 1 file changed, 147 insertions(+)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B2)
$ git checkout PAPAS_B3
Switched to branch 'PAPAS_B3'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git status
On branch PAPAS_B3
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git add Background.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git commit -m "Updated Background.txt and removed Test.py"
[PAPAS_B3 d440f6b] Updated Background.txt and removed Test.py
 1 file changed, 3 insertions(+), 1 deletion(-)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git rm Test.py
rm 'Test.py'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git status
On branch PAPAS_B3
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    Test.py


Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git commit -m "Remove Test.py"
[PAPAS_B3 35603f9] Remove Test.py
 1 file changed, 2 deletions(-)
 delete mode 100644 Test.py

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git checkout PAPAS_B2 -- Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git status
On branch PAPAS_B3
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Readme.txt


