# Markdown Practice

## Learning GIT

Git is a version control software

# Python Training 1

## Python Training 2

### Python Training 3

###### Python Traininh 4

This line is too long.

- Point 1
- Point 2

* One
* Two

``` First Class of Python Training ```

```
First Class of Python Training
```

```
Last login: Thu Mar 25 10:45:22 on ttys000
vidhichauhan@Admins-MacBook-Pro ~ % pwd
/Users/vidhichauhan
vidhichauhan@Admins-MacBook-Pro ~ % cd akademize/
cd: no such file or directory: akademize/
vidhichauhan@Admins-MacBook-Pro ~ % dir
zsh: command not found: dir
vidhichauhan@Admins-MacBook-Pro ~ % ls
Applications	Downloads	Music		python
Desktop		Library		Pictures	vroom.sh
Documents	Movies		Public
vidhichauhan@Admins-MacBook-Pro ~ % cls
zsh: command not found: cls
vidhichauhan@Admins-MacBook-Pro ~ % clear










vidhichauhan@Admins-MacBook-Pro ~ % mkdir akademize
vidhichauhan@Admins-MacBook-Pro ~ % ls
Applications	Downloads	Music		akademize
Desktop		Library		Pictures	python
Documents	Movies		Public		vroom.sh
vidhichauhan@Admins-MacBook-Pro ~ % cd akademize
vidhichauhan@Admins-MacBook-Pro akademize % code .
vidhichauhan@Admins-MacBook-Pro akademize % notepad .
zsh: command not found: notepad
vidhichauhan@Admins-MacBook-Pro akademize % ls
vidhichauhan@Admins-MacBook-Pro akademize % cd desktop
cd: no such file or directory: desktop
vidhichauhan@Admins-MacBook-Pro akademize % cd Desktop
cd: no such file or directory: Desktop
vidhichauhan@Admins-MacBook-Pro akademize % ls
vidhichauhan@Admins-MacBook-Pro akademize % notepad .
zsh: command not found: notepad
vidhichauhan@Admins-MacBook-Pro akademize % code .
vidhichauhan@Admins-MacBook-Pro akademize % code .
vidhichauhan@Admins-MacBook-Pro akademize % pwd
/Users/vidhichauhan/akademize
vidhichauhan@Admins-MacBook-Pro akademize % cd ..
vidhichauhan@Admins-MacBook-Pro ~ % cd .
vidhichauhan@Admins-MacBook-Pro ~ % pwd
/Users/vidhichauhan
vidhichauhan@Admins-MacBook-Pro ~ % cd akademize
vidhichauhan@Admins-MacBook-Pro akademize % ls
First Class.md
vidhichauhan@Admins-MacBook-Pro akademize % mkdir akademize-markdown-practice
vidhichauhan@Admins-MacBook-Pro akademize % cd akademize-markdown-practice
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % 
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % pwd
/Users/vidhichauhan/akademize/akademize-markdown-practice
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % ls
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % touch README.md
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % ls
README.md
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % code .
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % clear

vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % ls
README.md
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /Users/vidhichauhan/akademize/akademize-markdown-practice/.git/
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % ls -a
.		..		.git		README.md
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % clear





vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % clear













vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % touch test.txt
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % ls
README.md	test.txt
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % rm test.txt
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % clear



















vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git add README.md
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git log
fatal: your current branch 'master' does not have any commits yet
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git rm --cached README.md
rm 'README.md'
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % clear

vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % ls
README.md
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git add README.md
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git log
fatal: your current branch 'master' does not have any commits yet
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git commit -m "First commit"
[master (root-commit) 5468d0f] First commit
 1 file changed, 6 insertions(+)
 create mode 100644 README.md
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % git log
commit 5468d0f2817121ec36c8335d0e54a6dda8dd68b3 (HEAD -> master)
Author: Vidhi Chauhan <vidhi23chauhan@gmail.com>
Date:   Thu Mar 25 21:31:47 2021 +0530

    First commit
vidhichauhan@Admins-MacBook-Pro akademize-markdown-practice % 

```
