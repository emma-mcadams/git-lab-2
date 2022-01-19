1) Git Version 2.17.1
2) user.name=Emma McAdams
   user.email=em539719@ohio.edu
3) When I type git --help, common Git commands used in various situations are displayed. For example, commands for starting a working area, commands to work on the current change, etc
4) When I type git status, it displays there are no commits yet but the untracked files README.md and answers.md are present and displayed in red. It also displays the command "git add <file>..." to track files.
5)
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        new file:   README.md (displayed in green)
        answers.md (displayed in red)

nothing added to commit but untracked files present (use "git add" to track)

6)
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md
        new file:   answers.md
        (both displayed in green)

7)
On branch master
nothing to commit, working tree clean

8)
commit 57923c4884668522a2f584b9d8c051d5c13d2b49 (HEAD -> master)
Author: Emma McAdams <em539719@ohio.edu>
Date:   Tue Jan 18 19:15:37 2022 -0500

    Initial commit

9) 
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

10) Changes made in GitHub not reflected in local copy

11) 
Username for 'https://github.com': emma-mcadams
Password for 'https://emma-mcadams@github.com':
To https://github.com/emma-mcadams/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/emma-mcadams/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12)
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/emma-mcadams/git-lab
   57923c4..df07266  main       -> origin/main
Updating 57923c4..df07266
error: Your local changes to the following files would be overwritten by merge:
        README.md
Please commit your changes or stash them before you merge.
Aborting

Then after adding README.md again then running "git pull" again:

Updating 57923c4..60cc2b9
error: Your local changes to the following files would be overwritten by merge:
        README.md
Please commit your changes or stash them before you merge.
Aborting

13) .  ..  .git  .gitignore  README.md