# Demo 2
## Creating file locally then uploading/pushing to github:
### git init

Dont forget use "git status" to check for untracked files!
### git add . OR git add README.md
### git commit -m "Message"
Then create empty git repo on github, so can push there
### git remote add origin git@github.com:bchoongwj/demo-repo2.git
The link at the back is the SSH one
# First time you save, need to set up something called upstream. So:
### git push -u origin master
In future, subsequent times can use:
### git push
is default version for:
### git push origin master


# NEW BRANCH:
### git checkout -b New_Branch
-b name_of_file

# Check branch:
### git branch

# Switching back to master
### git checkout

# Switching back to new branch
### git checkout New_Branch

# To see code that youre merging:
### git diff New_Branch

# To merge branch with master:
### git merge New_Branch
OR
# Via pull request (more commonly used)
### git push -u origin New_Branch
Push new branch // 
Then check github "Compare and pull request"

# Delete branch:
### git branch -d New_Branch


# Undoing add
 ### git reset

 # Undoing commit
 ### git reset HEAD ~1
 HEAD points to last commit. 1 Means it will point to one commit further. Which means it unstages (add) and uncommits

 # See all commits:
 ### git log