Bundle 1(exercise1)
The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject (master)
$ mkdir GitPrijects

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject (master)
$ cd GitPrijects

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (master)
$ code.
bash: code.: command not found

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (master)
$ code .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (master)
$ git init
Initialized empty Git repository in C:/Users/The Gym/myproject/GitPrijects/.git/
The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (master)
$ git branch -m master main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git add .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git commit -m 'the frist change on main'
[main (root-commit) 3b6a915] the frist change on main
 2 files changed, 30 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git status
On branch main
nothing to commit, working tree clean

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git remote add origin https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions.git

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 773 bytes | 386.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git branch dev

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git branch
  dev
* main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git checkout -b dev
fatal: a branch named 'dev' already exists

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git checkout dev
Switched to branch 'dev'

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git branch test

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git checkout test
Switched to branch 'test'

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (test)
$ git checkout dev
Switched to branch 'dev'

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git branch -d test
Deleted branch test (was 3b6a915).

BUNDLE2 (exercise1)
The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (master)
$ git branch -m master main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git add .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git commit -m 'the frist change on main'
[main (root-commit) 3b6a915] the frist change on main
 2 files changed, 30 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git status
On branch main
nothing to commit, working tree clean

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git remote add origin https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions.git

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 773 bytes | 386.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git branch dev

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git branch
  dev
* main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git checkout -b dev
fatal: a branch named 'dev' already exists

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git checkout dev
Switched to branch 'dev'

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git branch test

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash
No local changes to save

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git add .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash
Saved working directory and index state WIP on dev: 3b6a915 the frist change on main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git add .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash
Saved working directory and index state WIP on dev: 3b6a915 the frist change on main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git add .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash
Saved working directory and index state WIP on dev: 3b6a915 the frist change on main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash pop
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (f0db1fe27456f883b36d7228d1ff1a2f3913210a)

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash
Saved working directory and index state WIP on dev: 3b6a915 the frist change on main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash list
stash@{0}: WIP on dev: 3b6a915 the frist change on main
stash@{1}: WIP on dev: 3b6a915 the frist change on main
stash@{2}: WIP on dev: 3b6a915 the frist change on main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash show -p stash@{0}
diff --git a/team.html b/team.html
new file mode 100644
index 0000000..d7b779d
--- /dev/null
+++ b/team.html
@@ -0,0 +1,15 @@
+<!DOCTYPE html>
+<html lang="en">
+<head>
+    <meta charset="UTF-8">
+    <meta name="viewport" content="width=device-width, initial-scale=1.0">
+    <title>Document</title>
+</head>
+<body>
+    <h2>welcome to our team</h2>

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash show -p stash{1}
error: stash{1} is not a valid reference

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash show -p stash@{1}
diff --git a/about.html b/about.html
new file mode 100644
index 0000000..a306978
--- /dev/null
+++ b/about.html
@@ -0,0 +1,19 @@
+<!DOCTYPE html>
+<html lang="en">
+<head>
+    <meta charset="UTF-8">
+    <meta name="viewport" content="width=device-width, initial-scale=1.0">
+    <title>Document</title>
+</head>
+<body>
+    <h3>the about page is avariable know</h3>

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (7bd519d372dac40cb23cd2179638202d6e2d1514)

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash pop stash@{2}
fatal: log for 'stash' only has 2 entries

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash -p show stash@{2}
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'show'

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash -p show stash@{2}
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'show'

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash show -p stash@{2}
fatal: log for 'stash' only has 2 entries

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash pop stash@{1}
Auto-merging about.html
CONFLICT (add/add): Merge conflict in about.html
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.md
        new file:   home.html
        new file:   team.html

Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both added:      about.html

The stash entry is kept in case you need it again.

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git commit -m 'the changes on about and home'
[dev 644f55b] the changes on about and home
 4 files changed, 135 insertions(+)
 create mode 100644 README.md
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 team.html

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git push 
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ $ git stash pop stash@{2}
bash: $: command not found

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ fatal: log for 'stash' only has 2 entries
bash: fatal:: command not found

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash pop stash@{0}
Auto-merging team.html
CONFLICT (add/add): Merge conflict in team.html
On branch dev
Your branch is up to date with 'origin/dev'.

Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both added:      team.html

no changes added to commit (use "git add" and/or "git commit -a")
The stash entry is kept in case you need it again.

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git commit -m 'chenges'
On branch dev
Your branch is up to date with 'origin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")      

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.
Aborting

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git add .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (dev)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git branch ft/bundle-2

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git branch
  dev
  ft/bundle-2
* main

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (main)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git add .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git commit -m 'another change'
[ft/bundle-2 6902688] another change
 2 files changed, 12 insertions(+)
 create mode 100644 services.html

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git push -u origin main
To https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because a pushed branch tip is behind its remote
hint: counterpart. If you want to integrate the remote changes, use 'git pull'
hint: before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git fetch origin

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git merge origin ft/bundle-2
merge: origin - not something we can merge

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git merge origin 
merge: origin - not something we can merge

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git merge origin/ft/bundle-2
merge: origin/ft/bundle-2 - not something we can merge

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git fetch

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git fetch orgin
fatal: 'orgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git fetch origin

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git merge origin/ft/bundle-2
merge: origin/ft/bundle-2 - not something we can merge

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git push --set-upstream origin ft/bundle-2
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 495 bytes | 165.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ get checkout main
bash: get: command not found

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 4 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)


BUNDLE 3(exercise1)
The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/faq-page)
$ git log 
commit 3d16c8543b98639c441d468ce665dbfb2f387503 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Kamikazi-Deborah <deborahkamikazi9@gmail.com>
Date:   Mon Apr 22 20:52:10 2024 +0200

    the change on faq

commit 7165d4eb458ea7d0d595739cb0f326f74b7437ed (origin/ft/contact-page, ft/contact-page)
Author: Kamikazi-Deborah <deborahkamikazi9@gmail.com>
Date:   Mon Apr 22 20:42:33 2024 +0200

    the change on contact page

commit 37aa241624ff24a451530ac3b0018c809626e914
Author: Kamikazi-Deborah <deborahkamikazi9@gmail.com>
Date:   Mon Apr 22 20:15:33 2024 +0200

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/faq-page)
$ git add .

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/faq-page)
$ git commit -m 'another change'
[ft/faq-page fd4c437] another change
 2 files changed, 1 insertion(+), 194 deletions(-)

The Gym@DESKTOP-3NHLQBK MINGW64 ~/myproject/GitPrijects (ft/faq-page)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 385 bytes | 192.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/Kamikazi-Deborah/Gym-Git-Exercise-Solutions.git
   3d16c85..fd4c437  ft/faq-page -> ft/faq-page
 

 BUNDLE3 (exercise2);