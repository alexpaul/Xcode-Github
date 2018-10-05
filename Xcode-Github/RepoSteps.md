## Steps to create repo 

1. Create Xcode Project 
1. Navigate to project in terminal and `cd ProjectFolder` 
1. Initialize (create your local repository) using `git init` 
1. Check status of local repository using `git status`
1. Add files to be changed and commited by running `git add filename` or `git add .` N.B be careful as to what files are being commited if doing an <b>`git add .`</b>
1. Add commit message by running `git commmit -m "initial commit"`
1. Navigate to [Github.com](https://www.github.com) and create a new repository 
1. Copy `git remote add <url>` url from your newly created Github remote repo
1. Paste in terminal and press enter 
1. Run `git push --set-upstream origin master`

At this point if all went well you should be able to refresh your Github page and see your newly repo
