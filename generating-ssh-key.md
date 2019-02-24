# Generating an SSH key 
## About SSH key
Using the SSH protocol, you can connect and authenticate to remote servers and services. With SSH keys, you can connect to GitHub without supplying your username or password at each visit.

* type `pwd` to make sure you're in current project folder directory
* type `ls .ssh` to check if there already exists .ssh directory
* type `mkdir .ssh` to create a directory called .ssh
* type `cd .ssh` to change to .ssh directory
* type `ssh-keygen -t rsa -C "youremail@email.com"` to generate key, you'll be prompted to where to save the file, press `Enter` to accept the default, then press `Enter` to empty pressphrase.
* Go to Github SSH key setting page, and add SSH-key based on *id_rsa.pub* file in local computer.
* Then return to terminal, type `ssh -T git@github.com`  the setup is done!

--------------------------

When updating remote URL, you can type:
`git remote set-url origin git@github.com: git@github.com:fzhang22/new.git`
