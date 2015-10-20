# mydoc

Changes:
2015-10-19 Add items 1-5
2015-10-19 Update from website

1- Launch "Git Bash"

2- Create a directory on your Windows machine where you want
to clone from Git repo.
mkdir c:\gitstuffs

3- Transform current directory into a Git repo.
$ cd /c/gitstuffs
$ git init

4- Clone from my git repot
$ git clone https://github.com/fgunady/mydoc.git
Cloning into 'mydoc'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.

5- Start tracking this file
$ git add README.md

6- 
$ git diff --cached

7-  
$ git commit -m 'Update doc'
[master f640872] Update doc
 1 file changed, 16 insertions(+)

8-
$ git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 461 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/fgunady/mydoc.git
   b695b7d..f640872  master -> master
