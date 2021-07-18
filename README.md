# learning github
 """ 
 As there is no any commit so the 
 git status will show no commit yet 
 there are untracked files readme.md is not tracked
 yet.

git add README.md will take us to staging area
we can't commit unadded file

 """
## git commands

git init -> initializes a repo 
git add -> add/tracks the file to staging
git commit -> pushed the added changes/file to local repo
git diff -> shows difference between directory and staging
git status -> shows the tracking/adding/commiting infos of the current files
git restore --staged file_neme -> unstage the file_name
git branch  -> it shows the current and all branches in a repository
git add . -> it adds all the files in that folder to the repo so handle it carefully or never use this
git log -> shows the commit logs
git reset --soft HEAD~1 -> reseet the repo to the privious commit
git checkout commit id -> it take us to the perticular commit to return to master we write git checkout master
git checkout branch_name -> switch us to a the branch given in branch_name


