Git and GitHub
## Dictionary of concepts
- Git: Software
- Github: Website

## Conceptual area
- Dev.area: folder where I dev my project
- Stageing area: intermediate area to organize my commit
	- Why do I use staging area
- Local repo: Git timeline - with my commits
- remote repo: 

## Check the status of Git
use `git status` to check whether there are files changed or added but not commited

## what happen if commit without -m
it will pop up an editor to allow you write more detail description

## .gitignore
*.csv
!dataset.csv

## create link between local and remote
git remote add <local_repo> <remote_ssh>

## push local changes to remote repo
git push

## bring the remote changes back to local repo
git pull

## add a picture in the markdown file
![title for the figure](./images/1683879439910.png)

## regretting a commit
git revert <commit ID>         # safe choice
git reset --hard <commit ID>   # not that safe but ok

