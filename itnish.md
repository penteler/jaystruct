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

C:\Users\surin\vcsol\jaystruct>cd..

C:\Users\surin\vcsol>git clone https://github.com/penteler/rugin.git
Cloning into 'rugin'...
remote: Enumerating objects: 105, done.
remote: Counting objects: 100% (105/105), done.
remote: Compressing objects: 100% (81/81), done.
remote: Total 105 (delta 35), reused 88 (delta 18), pack-reused 0
Receiving objects: 100% (105/105), 990.62 KiB | 3.15 MiB/s, done.
Resolving deltas: 100% (35/35), done.

C:\Users\surin\vcsol>cd rugin

C:\Users\surin\vcsol\rugin>dir
 Volume in drive C is Acer
 Volume Serial Number is 7C30-8CE9

 Directory of C:\Users\surin\vcsol\rugin

11-04-2024  14:56    <DIR>          .
11-04-2024  14:56    <DIR>          ..
11-04-2024  14:56             1,765 ernO.md
11-04-2024  14:56             2,290 mrCith.md
               2 File(s)          4,055 bytes
               2 Dir(s)  20,292,620,288 bytes free

C:\Users\surin\vcsol\rugin>git checkout tobe
branch 'tobe' set up to track 'origin/tobe'.
Switched to a new branch 'tobe'

C:\Users\surin\vcsol\rugin>dir
 Volume in drive C is Acer
 Volume Serial Number is 7C30-8CE9

 Directory of C:\Users\surin\vcsol\rugin

11-04-2024  14:57    <DIR>          .
11-04-2024  14:57    <DIR>          ..
11-04-2024  14:57             6,604 accessingArguments.md
11-04-2024  14:57    <DIR>          calculator
11-04-2024  14:56             1,765 ernO.md
11-04-2024  14:57            34,582 fil
11-04-2024  14:57             3,257 gitup.md
11-04-2024  14:57               145 inish.md
11-04-2024  14:57             4,028 mrCith.md
11-04-2024  14:57             1,583 one.rs
               7 File(s)         51,964 bytes
               3 Dir(s)  20,288,466,944 bytes free

C:\Users\surin\vcsol\rugin>fil
'fil' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\surin\vcsol\rugin>vim fil
'vim' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\surin\vcsol\rugin>git config --global --edit
hint: Waiting for your editor to close the file...
←[23;0;0t
Press ENTER or type command to continue

C:\Users\surin\vcsol\rugin>
git pull
warning: redirecting to https://github.com/penteler/jaystruct.git/
remote: Enumerating objects: 24, done.
remote: Counting objects: 100% (24/24), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 17 (delta 6), reused 17 (delta 6), pack-reused 0
Unpacking objects: 100% (17/17), 3.17 KiB | 29.00 KiB/s, done.
From https://www.github.com/penteler/jaystruct
   3a9667c..77f37e8  main       -> origin/main
Updating 3a9667c..77f37e8
Fast-forward
 index.html             |   5 +-
 itnish.md              | 145 +++++++++++++++++++++++++++++++++++++++++++++++++
 js/math/graph.js       |   7 +++
 js/primitives/point.js |   5 ++
 4 files changed, 160 insertions(+), 2 deletions(-)
 create mode 100644 itnish.md
