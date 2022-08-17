
# for rollback to a specific commit in remote 
# ref -https://stackoverflow.com/questions/5816688/resetting-remote-to-a-certain-commit
git reset --hard 1157cdcf66c328ca0fa02c01a4d5db82e53dd719 <br />
git push --force origin master <br />


# create a new branch from specific commit 
git reset --hard 1157cdcf66c328ca0fa02c01a4d5db82e53dd719 <br />
git switch -c master3 <br />
