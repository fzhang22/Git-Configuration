# synchronization between Git repository and Github repository 

## Create a local copy with clone:
* In terminal, type `pwd` into the local file directory from which you want to clone the project, e.g  "/c/zf/SIT/Github"
* To create a local copy with clone, type `git clone git@github.com:fzhang22/demo.git` (likewise "git clone "your SSH URL address")
* To check the file directory, type `ls -al`
* If you want to change the file name, type `git clone git@github.com:fzhang22/demo.git mydemo`, in this case, "my demo" is the result name that you want to change to.

-----------------------------------------------------------------------
Now we downloaded a new folder contains files. We want to copy the folder to our Git, then unzip the folder.
* type `cp -R /c/zf/SIT/Github/initializr-verekia-4.0/* .`  All the files were copied into Github certain directory
* Then type `git add . ` Then all the files were added into Git master branch
* Finally, commit these new added files, type `git commit -m"Adding existing file"`
* Check the status `git status`
------------------------------------------------------------------------
When you want to push all the files into master branch in Github, type:
`git push`

When you want to pull all the files from Github to Git, type:
`git pull`
