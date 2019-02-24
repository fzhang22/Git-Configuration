# Some useful git branch commands
## Local branch
In master branch, for creating a branch, type command as follow:
`git checkout -b ipsum` which the name is called ipsum

After decided to push this branch to Github, type:
`git push -u origin ipsum`

## Merge locally
back to master branch
`git checkout master`

Firstly, get everything updated to Git from Github
`git pull`

Secondly, merge branch type:
`git merge ipsum`

Thirdly, bring all these merge in Git back to Github again:
`git push`

Fourthly, delete the branch locally
`git branch -d ipsum`

Checkout the branch status
`git branch -a`

---------------------------------------------------------
