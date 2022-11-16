# How to Use Github
Now that you have git set up on your computer and a copy of the git repository, you have to learn how to use it properly. First, make sure your terminal is in the root of the repository folder or else git won't work properly.

## `git pull`
Pull is the first command you will be learning and what it does is fetch all the updates from the repository. So if I make an update, and you run `git pull` my update will be reflected on your computer. It is very important to pull before doing any work so you don't overwrite any changes.

## `git add`
In order to add your work to the git repository, you need to use `git add`. It's specific use is `git add [filename]` but you can also use `git add [directory]` to add a directory or `git add .` to add the entire project (not recommended).

## `git commit`
You've added your changes but now what? git knows they exist, but you need to tell git to finalize them in a commit. A commit locks in your changes and lets you push them to the repository. To make a commit do `git commit -m "A helpful message describing the commit in a few words"`.

## `git push`
Now that all your changes have been made and committed, you need to push them to the repository in order for them to be pulled by the rest of us. To do so, just use `git push`.

## Other Commands
Git and github are much much more complicated and I recommend doing some research on them on your own, here is a [helpful cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf) for some other commands. I recommend learning how git status works as it is very helpful when properly staging commits.