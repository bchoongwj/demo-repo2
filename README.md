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
### git push origin main