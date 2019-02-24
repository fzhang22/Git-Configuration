# Git Tag
## Introduction
Git has the ability to tag specific points in a repository’s history as being important. Typically, people use this functionality to mark release points (v1.0, v2.0 and so on)

Some useful git tagging commands are listed below:

`git tag unstable develop`  Give tag name: unstable on develop branch

`git tag stable master` Give tag name: stable on master branch

`git log --oneline`  Check ID of tag, ID could be userful later for certain operations

`git tag` List all the tags

`git log --oneline`
`git tag -a v0.1-alpha -m"Realease 0.1 (Alpha)" 879045f`
`git show v0.1-alpha`

Add annotated tag, "879045f" is id of tag to be annotated

`git push origin stable` Push the tag to Github

`git push --tags` Push all the tags to Github

`git tag -d v0.1-alpha` Delete the certain tag

`
