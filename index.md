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
## Branch creation
In order to create new branch enter the command
```
git branch <branch_name>
or 
git checkout -b <branch_name>
```
## Merge
In order to join two or more development histories together move to master brnach and enter the command 
```
git merge <branch_name>
```