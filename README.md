- git init : initialize current folder as a git repository
- git clone <URL> : brings the git repo from <URL> to current folder
- git add filename: to insert file to the staging area
- git status: display status of the repository
- git commit: open a text editor to write commit message
- git commit -m "MESSAGE": write MESSAGE as a commit without a text editor
- git log : dispaly history of our commits
- git log --oneline : show the shorter oneline commit
- git diff : compare current uncommitted  state with last known git state
- git diff --staged : runs git diff between  the staging area and last known state
- git diff HEAD~<NUMBER> : compares HEAD with commit <NUMBER> ago (relative)
- git diff <HASH> : compares HEAD with the commit in <HASH>
- git restore --source <HASH OR HEAD~> <FILE> : restore file to <HASH OR HEAD~>
- git checkout <HASH OR HEAD~> <FILE> : restore file to <HASH OR HEAD~>
- git checkout <HASH OR HEAD~> : if you forget the file, you end up in detach
- git checkout main: go back to main
- git switch main : go back to main
- git remote add <NAME> <URL> : adds the <URL> as a remote with the name <NAME>
<NAME> is by convention  called origin
- git remote -v : look at all the remote you have
- git push `<WHERE> <WHAT>` : pushes the <WHAT> branch to <WHERE> => git push origin main
- git remote rm `<NAME>` : removes the remote called <NAME>
- git pull `<WHERE> <WHAT>` : pull the branch in to local computer

THE END
