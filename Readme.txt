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
Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git add Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git commit -m "Insert commands"
[PAPAS_B3 dee2389] Insert commands
 1 file changed, 201 insertions(+)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git checkout PAPAS_B4
Switched to branch 'PAPAS_B4'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git checkout PAPAS_B3 -- Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git rm Test.py
rm 'Test.py'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git commit -m "Removed Test.py"
[PAPAS_B4 d195f97] Removed Test.py
 2 files changed, 201 insertions(+), 2 deletions(-)
 delete mode 100644 Test.py

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git status
On branch PAPAS_B4
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git add Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git commit -m "Insert commands"
[PAPAS_B3 dee2389] Insert commands
 1 file changed, 201 insertions(+)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B3)
$ git checkout PAPAS_B4
Switched to branch 'PAPAS_B4'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git checkout PAPAS_B3 -- Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git rm Test.py
rm 'Test.py'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git commit -m "Removed Test.py"
[PAPAS_B4 d195f97] Removed Test.py
 2 files changed, 201 insertions(+), 2 deletions(-)
 delete mode 100644 Test.py

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git status
On branch PAPAS_B4
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git add Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git commit -m "Insert commands"
[PAPAS_B4 9be7f51] Insert commands
 1 file changed, 31 insertions(+)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git checkout PAPAS_B4
M       Readme.txt
Already on 'PAPAS_B4'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git add Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git commit -m "Added git commands in PAPAS_B4 branch"
[PAPAS_B4 68a04bf] Added git commands in PAPAS_B4 branch
 1 file changed, 14 insertions(+)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git status
On branch PAPAS_B4
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (PAPAS_B4)
$ git checkout master
Switched to branch 'master'

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git checkout PAPAS_B1 -- Profile.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git checkout PAPAS_B2 -- Education.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git checkout PAPAS_B3 -- Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git checkout PAPAS_B3 -- Background.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git checkout PAPAS_B4 -- Readme.txt

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Background.txt
        modified:   Education.txt
        modified:   Profile.txt
        modified:   Readme.txt


Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git commit -m "All Information combined"
[master 230e5bd] All Information combined
 4 files changed, 290 insertions(+), 3 deletions(-)

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git status
On branch master
nothing to commit, working tree clean

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git remote add origin https://github.com/Thea-18/PAPAS_IT120_ACT1.git

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (master)
$ git branch -M main

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (main)
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 12 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (13/13), 2.44 KiB | 227.00 KiB/s, done.
Total 13 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/Thea-18/PAPAS_IT120_ACT1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (main)
$ git push origin PAPAS_B1
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.49 KiB | 254.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'PAPAS_B1' on GitHub by visiting:
remote:      https://github.com/Thea-18/PAPAS_IT120_ACT1/pull/new/PAPAS_B1
remote:
To https://github.com/Thea-18/PAPAS_IT120_ACT1.git
 * [new branch]      PAPAS_B1 -> PAPAS_B1

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (main)
$ git push origin PAPAS_B2
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.52 KiB | 310.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'PAPAS_B2' on GitHub by visiting:
remote:      https://github.com/Thea-18/PAPAS_IT120_ACT1/pull/new/PAPAS_B2
remote:
To https://github.com/Thea-18/PAPAS_IT120_ACT1.git
 * [new branch]      PAPAS_B2 -> PAPAS_B2

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (main)
$ git push origin PAPAS_B3
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 12 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.72 KiB | 293.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'PAPAS_B3' on GitHub by visiting:
remote:      https://github.com/Thea-18/PAPAS_IT120_ACT1/pull/new/PAPAS_B3
remote:
To https://github.com/Thea-18/PAPAS_IT120_ACT1.git
 * [new branch]      PAPAS_B3 -> PAPAS_B3

Kea Papas@LAPTOP-H175QIKR MINGW64 ~/PAPAS_IT120_Act1 (main)
$ git push origin PAPAS_B4
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 12 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 2.06 KiB | 421.00 KiB/s, done.
Total 12 (delta 7), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (7/7), completed with 1 local object.
remote:
remote: Create a pull request for 'PAPAS_B4' on GitHub by visiting:
remote:      https://github.com/Thea-18/PAPAS_IT120_ACT1/pull/new/PAPAS_B4
remote:
To https://github.com/Thea-18/PAPAS_IT120_ACT1.git
 * [new branch]      PAPAS_B4 -> PAPAS_B4





