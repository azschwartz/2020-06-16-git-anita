# 2020-06016 Git
## Local
- `git init`: create a git repository in the current directory
- `git status`: tells you what is going on
- `git add <FILENAME(S)>`: adds a file(s) to the staging area
- `git commit`: opens up your edit, commits the file(s) added in the staging area in to the repository, you need to type a comment at the top of the file and save it.
- `git log`: see the history (via keys = HEAD~<number> of the repository
- `git log --oneline`: shorter one line version of `git log`
- `git diff HEAD~<number> or short key <FILENAME>`: display the difference from your current version of <FILENAME> to the version of the <FILENAME> in HEAD~<number>
- `git --staged <FILE>`: shows difference of <FILE> staged
- `git checkout HEAD~<number> or short key <FILENAME>: restore the file to version in HEAD~<number>
## Remote
- `git remote add <name> <url>`: gives the remote URL and associates it with NAME
- `git push <where> <what>`: e.g. `git push origin master` takes master branch on your local computer and pushes it to the origin location
- `git pull <where> <what>`: e.g. `git pull origin master` takes remote master branch, and brings it to your local computer
