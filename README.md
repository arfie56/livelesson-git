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
