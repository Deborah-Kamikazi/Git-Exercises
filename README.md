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