# Main commands GIT

## New repository initiation

Go to the project files folder and enter the command
```
git init
```

## Adding file in order to commit

Create file with needed content and enter the command
```
git add <filename>
```
## Commiting files to confirm changes
Enter the command
```
git commit -m "<comments>"
```
## Pushing repository changes to remote reference
In order to update remote refs using local ones enter the command
```
git push
```
## Showing commited logs
To show list of commited logs enter the command
```
git log 
or 
git log --oneline
```
To add options to your log command type
```
git reflog <subcommand> <options>
```

## Branch creation
In order to create new branch enter the command
```
git branch <branch_name>
or 
git checkout -b <branch_name>
```
## Merge branch
In order to join two or more development histories together move to master branch and enter the command 
```
git merge <branch_name>
```
## Rebase branch
In order to reapply commits on top of each other move to master branch and enter the command 
```
git rebase <branch_name>
```
## Restoring working tree files

Restore specified paths in the working tree with some contents from a restore source. If a path is tracked but does not exist in the restore source, it will be removed to match the source. To do so type
```
git restore <branch_name>
```
## Adding files to ignore 
In order to specifie intentionally untracked files to ignore you have to write save them in file and name it
```
.gitignore
```
## Deleting branch
In order to delete branch enter the following command 
```
git branch -d <branch_name>
```