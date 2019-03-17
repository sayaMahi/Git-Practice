Practicing Git.

https://guides.github.com/features/mastering-markdown/
https://github.com/joshnh/Git-Commands

# Git Tips

## Log

1. git log  

> logs all the commits

2. git diff <commit#1> <commit#2>

> shows diff b/n 2 commits. first 4 digits are okay.

3. git log --stat

> logs all commits,but also shows which files are changed.
> q to quit log.

## Colored Output

1. git config --global color.uri auto

## Checkout

1. git checkout <checkout#>

> If the checkout # is a old version, then you are in detached Head state. Any changes made in detached head state, things get complicated.

## Staging Area

1. git add <filename> or git add . (to add all files)
 
2. git reset <file name>
> to remove file from Staging area
  
3. git status
> gives status about staging area

4. git commit -m "<comment>"  or git commit => opens editor to add comment
  
## Different Directories

Working Directory      Staging Area       Repository Commit

   File 1                File 1             commit [File1, File 2]
   File 2*               File 2
   
   
   git diff
   > gives diff b/n *Working Directory* and *Staging Area*
   
   git diff --staged
   > gives diff b/n *Staging Area* and *Repository Area*
   
