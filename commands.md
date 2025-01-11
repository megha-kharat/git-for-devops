GIT- (Global information tracker)- It is a VCS (version control system) used as a source code manager to keep a track of the versions of the code.

1. Go to the repo which u want to be tracked.
2. Run command --> git init
3. To check which all files are tracked or untracked in the initialized repo --> git status
4. If you want to untrack the file --> git rm --cached demo.txt
5. to commit the changes --> git commit -m "Any message"
6. To restore a file which was deleted --> git restore demo.txt
7. To configure name and email to know who modified/created the file-
    git config --global user.name "megha.kharat"
    git config --global user.email "meghakharat447@gmail.com"
8. to see the commit history --> git log
9. to create a new branch from master --> git checkout -b dev (here dev is the new branch name)
10. To come back to master branch --> git checkout master or git switch master
11. To see how many branches are created --> git branch
12. head tells us the latest commit of that particular branch.
13. to see a compact summary of commits use --> git log --oneline
