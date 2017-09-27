# Git

Coding Cougs

---

## Follow along!

* https://tinyurl.com/codingcougs-git


---

## What is Git?

* Distributed Version Control System
* Written by Linus Torvalds (The linux guy)
* Widely used industry tool


---

## What is Git good for?

* Having a "Safe space" to work (branches)
* Collaborating with others
* Tracking file changes


---

## Git Clients

* Command Line <i class="fa fa-linux" aria-hidden="true"></i> <i class="fa fa-apple" aria-hidden="true"></i> <i class="fa fa-windows" aria-hidden="true"></i>
  * https://git-scm.com/
* Source Tree <i class="fa fa-apple" aria-hidden="true"></i> <i class="fa fa-windows" aria-hidden="true"></i>
  * https://www.sourcetreeapp.com/
* gitk <i class="fa fa-linux" aria-hidden="true"></i> <i class="fa fa-apple" aria-hidden="true"></i> <i class="fa fa-windows" aria-hidden="true"></i>
  * https://git-scm.com/
* TortoiseGIT <i class="fa fa-windows" aria-hidden="true"></i>
  * https://tortoisegit.org/


---

## Install Git
https://git-scm.com/


---

## Got Git?
open terminal or command prompt

~~~~
git version
~~~~
or
~~~~
git --version
~~~~

Note: Lets make sure everyone has git installed

---

## Overview
* Use git cli
* Modify file
* Make commits(saves)
* Make branch
* Merge branch into master

---

## Create a new folder
* Name it "learn-git", maybe?
<p></p>
* Open a terminal/CMD and change the directory to "learn-git"
  * Windows: cd ~/Desktop/learn-git
  * OSX: cd ~/Desktop/learn-git

---

## Git Init
~~~~
git init
~~~~
* Creates a new **`*repository*`**
* Transforms your folder into a **`*repository*`**

---

## Git Status
~~~~
git status
~~~~
* View the status of your **`*repository*`**
* Shows you **`*staged*`** and **`*unstaged*`** changes
* **`*staged:*`** changes you want to save
* **`*unstaged:*`** changes you don't want to save

---

## Let's add a file
~~~~~
git status
~~~~~
* Create a text file in your repository

~~~~~
git status
~~~~~
* What is different?

---

## Git Add
~~~~
git add [file-name]
~~~~
* Adds, or **`*stages*`**, changes for commit
* Says: "Okay, lets prepare to save this"


---

## Git Commit
~~~~
git commit -m "short message"
~~~~
* Takes your **`*staged*`** changes and saves them in the log
<p></p>

On first setup:
~~~~
git config --global user.email "your@email.co"
git config --global user.name "Your Name"
~~~~

---

## Git log
~~~~
git log
~~~~
* Lets you see your **`*commit*`** history. (History of saves)
* This is where gitk and Source Tree help with visualizing commits

~~~~
gitk
~~~~

---

## Git Checkout
~~~~
git checkout [file-name]
~~~~
* The undo button
* Lets you "go back" to the previously committed state of a file(s).
* Forgets modifications shown in **`*staged*`** and **`*unstaged*`** files.


---

## Git Branch
~~~~
git branch [your-branch-name]
~~~~
* Want to work on a new feature without breaking the project? Make a **`*branch*`**!
* Branches are like a sandbox


---

## Git Checkout
~~~~
git checkout [branch-name]
~~~~
* This command also allows you to **`*checkout*`** other branches.
* Remember that this command, when given a file name, forgets the changes made to that file after the latest commit.

~~~~
git checkout [file-name]
~~~~
vs
~~~~
git checkout [branch-name]
~~~~


---

## Git Branch and Checkout
~~~~
git checkout -b [branch-name]
~~~~
* This combines the **`*branch*`** creation and **`*checkout*`** commands together
* Useful because the two commands are used frequently and together


---

## Git Merge
~~~~
git merge [branch-name]
~~~~
* Sandbox branch works? Time to recombine with the rest of the project
* Merging brings the changes you were working on back into your current branch

---

## Resources

http://ohshitgit.com/
https://sethrobertson.github.io/GitFixUm/fixup.html

---

## git commands

~~~~~
git version
git init
git status
git add
git commit
git log
gitk
~~~~~

---

## git commands

~~~~~
git checkout [file-name]
git checkout [branch-name]
git checkout -b [new-branch-name]
git branch
git branch [new-branch-name]
git merge [branch-name]
~~~~~
