ANS 1 - I think --global means that the changes we made or will make, be it creating or naming files or folders, pushing pulling, etc will be made on the system as a whole, and the "user" (me) has full access to all files of the system, not just a particular part of it

According to the git manual two things would happen :
It would only apply inside that one repo, so you'd have to repeat it for every project.
If you ran it outside a repo, it would fail with an error, since there's no repo to save the setting in.

ANS 2 - ".git"

FETCH_HEAD  HEAD  config  description  hooks  index  info  logs  objects  packed-refs  refs 
these are the things i found inside .git

ANS 3 - 

On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   week02/W2-the-terminal.md
        modified:   week02/notes.md
        modified:   week03/lab2_cc_2026.ipynb
        modified:   week04-05/lab3_cc.ipynb

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        week06/

no changes added to commit (use "git add" and/or "git commit -a")


this is what i saw after git status bcz i created this repo/folder right before starting this lab.

ANS 4 -the .venv and pycache files that we just added to .gitignore are not visible in the git status anymore.

ANS 5 - gitignore should be committed so that the system knows which files to ignore, and to keep track of that, gitignore itself mustnt be ignored (also it could be an infinite loop?)

ANS 6 - README got moved into the "staging area", from untracked files to changes to be committed.

ANS 7 - [main fccd8ea] Lab work so far
 6 files changed, 2206 insertions(+), 2206 deletions(-)
 create mode 100644 week06/lab04notes.md

ANS 8 - "hash" - to identify the commit, give an address to that checkpoint

ANS 9 - add commit status log

ANS 10 - because a readme is usually the 'coverpage' of a repo, it is usually used to give a project summary in repos.

ANS 11 -  gh auth login connected the terminal to my github account so it knows which account's repos to access, and to not require authorization repetitively when i try to push smth.

ANS 12 - the README for the same reasons mentioned in ans10

ANS 13 - yes my latest commit is visible, working tree is clean, and nothing is in the staging area now

ANS 14 - well if a repo is private, atleast it allows me to access all prev versions of that file or folder which wouldnt have been the case if the repo didnt exist at all.