Microsoft Windows [Version 10.0.19042.985]
(c) Microsoft Corporation. All rights reserved.

C:\Users\surin\vcsol>git clone https://github.com/penteler/jaystruct.git
Cloning into 'jaystruct'...
remote: Enumerating objects: 24, done.
remote: Counting objects: 100% (24/24), done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 24 (delta 3), reused 23 (delta 2), pack-reused 0
Receiving objects: 100% (24/24), done.
Resolving deltas: 100% (3/3), done.

C:\Users\surin\vcsol>code

C:\Users\surin\vcsol>cd jaystruct

C:\Users\surin\vcsol\jaystruct>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   js/math/graph.js
        modified:   js/primitives/point.js

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\surin\vcsol\jaystruct>git add .

C:\Users\surin\vcsol\jaystruct>git commit -m "first commit from this device"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'surin@DESKTOP-UKFUBCR.(none)')

C:\Users\surin\vcsol\jaystruct>git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date

C:\Users\surin\vcsol\jaystruct>git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date

C:\Users\surin\vcsol\jaystruct>git config global user.email "impromooray@gmail.com"
error: key does not contain a section: global

C:\Users\surin\vcsol\jaystruct>git config --global user.email "impromooray@gmail.com"

C:\Users\surin\vcsol\jaystruct>git config --global user.name "penteler"

C:\Users\surin\vcsol\jaystruct>git commit -m "first commit from this device"
[main 11d06ee] first commit from this device
 3 files changed, 15 insertions(+), 2 deletions(-)

C:\Users\surin\vcsol\jaystruct>git push -u origin main
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 2 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (8/8), 805 bytes | 57.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/penteler/jaystruct.git
   3a9667c..11d06ee  main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\surin\vcsol\jaystruct>git pull
Already up to date.

C:\Users\surin\vcsol\jaystruct>
