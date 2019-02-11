pull all branches

$ git remote update  
$ git pull --all

for remote in `git branch -r `; do git branch --track $remote; done
