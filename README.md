# PLPBasicGitAssignment
malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (master)       
$ git init
Initialized empty Git repository in C:/PLPBasicGitAssignment/.git/    

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (master)       
$ git remote add origin https://github.com/Maluba96/PLPBasicGitAssignment.git

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (master)       
$ git add hello.txt

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (master)       
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Maluba96/PLPBasicGitAssignment.git'
 create mode 100644 hello.txt

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Maluba96/PLPBasicGitAssignment.git'

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (master)
$ git branch
* master

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (master)
$ git branch -m main

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git add hello.txt

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git commit -m "Add hello.txt with a greeting"
On branch main
nothing to commit, working tree clean

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push -u origin main
To https://github.com/Maluba96/PLPBasicGitAssignment.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Maluba96/PLPBasicGitAssignment.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 878 bytes | 125.00 KiB/s, done.
From https://github.com/Maluba96/PLPBasicGitAssignment
 * [new branch]      main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main


malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git add hello.txt

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git commit -m "Add hello.txt with a greeting"
On branch main
nothing to commit, working tree clean

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push -u origin main
To https://github.com/Maluba96/PLPBasicGitAssignment.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Maluba96/PLPBasicGitAssignment.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git pull origin main
From https://github.com/Maluba96/PLPBasicGitAssignment
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git add .

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git commit -m "Resolved merge conflicts"
On branch main
nothing to commit, working tree clean

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push -u origin main
To https://github.com/Maluba96/PLPBasicGitAssignment.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Maluba96/PLPBasicGitAssignment.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push --set-upstream origin main
To https://github.com/Maluba96/PLPBasicGitAssignment.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Maluba96/PLPBasicGitAssignment.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git add .

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git commit -m "Add hello.txt with a greeting"
On branch main
nothing to commit, working tree clean

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push --set-upstream origin main
To https://github.com/Maluba96/PLPBasicGitAssignment.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Maluba96/PLPBasicGitAssignment.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push -u origin main
To https://github.com/Maluba96/PLPBasicGitAssignment.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Maluba96/PLPBasicGitAssignment.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
Merge branch 'main' of https://github.com/Maluba96/PLPBasicGitAssignment
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git pull origin main
From https://github.com/Maluba96/PLPBasicGitAssignment
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git pull origin main --allow-unrelated-histories
From https://github.com/Maluba96/PLPBasicGitAssignment
 * branch            main       -> FETCH_HEAD
Merge made by the 'ort' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$ git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 551 bytes | 551.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Maluba96/PLPBasicGitAssignment.git
   118e3a0..79ac0c0  main -> main
branch 'main' set up to track 'origin/main'.

malub@grassrootsoccer MINGW64 /c/PLPBasicGitAssignment (main)
$
