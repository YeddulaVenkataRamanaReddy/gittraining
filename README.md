# GIT NOTES
- 'git init' : intialize current folder as a git repository
- 'git clone <URL>': brings the git repo from <URL> to current folder
- 'git status' : tells us what we need to know about our repository
- 'git add<FileName>' : add file to the staging area
- 'git commit' or 'git commit -m "message"':writes messages as commit
- 'git log' : shows the history of our commits
- 'git log --oneline' : shows the shorter oneline commit

#Remotes
- 'git remote add <NAME> <URL> ': adds the <URL> as a remote with the name <NAME>
   - <NAME> : is by convention called 'origin'
- 'git remote -v' : looks at all the remotes you have
- 'git push <where> <what> ': takes your repository and pushes the  <what> to <where>
- 'git remote rm <NAME> : removes the remote called <NAME>
- 'git pull <where> <what> ': pulls the <what> branch in<where> to local computer 

## Branches

- 'git branch {NAME} : to create the branch
- 'git switch {NAME} : switch to the Branch Name

- Merging branches remotely refers to Pull Request or merge request
- to upadatea PR, we make the changes to the branch locally and re -push

- a merge conflict will happen after a pr has been raised 

- 'git fetch' :update your git log without making changes to your files 
   -'git fetch --prune': update your log and also remove delected remote branches


- git push -f :force push to the remote 
- git push --force-with-lease: more mindfull of collabrations
