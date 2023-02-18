# git_basic_commands
Basic Commands for Git

## Add remote repository.
 git remote add <remote_name> <git_repo>
 git remote add origin https://github.com/tmuttaqueen/AdvancedCPP.git
 
 Here, origin is the name of the remote repo. We can set any name.
## Check remote repos.
 git remote -v

## Pull from remote to current branch.
 git pull <remote_name> <branch_name>
 git pull origin master
 
When 1st time pulling,
 git pull origin main --alow-unrelated-histories

## Push current local branch to remote branch.
 git push -u <remote_name> <branch_name>
 git push -u origin main
