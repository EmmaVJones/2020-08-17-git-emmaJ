# 2020-08-17

## Local
- `git init`: create git repo in current folder
- `git config --global user.name  "EmmaVJones"
- `git config --global user.email "emma.v.jones@icloud.com"



- `git status` current state of repo
- `git add filename` add filename to staged area
- `git commit` commits file(s) with message, use nano by default config
- `git log` shows you history 
   - `git log --oneline` smaller output
- `HEAD` where you are looking at in commit history
- `git diff` find differences in commit history
- `git diff --staged` find differences only in staged content
- `git commit -m "commit message"` commit shortcut to skip nano


## Remotes
- `git remove add origin <URL>` adds url with the name origin
- `git push origin master` pushes master branch to origin
- `git pull origin master` pulls master branch from origin

- You can make changes to different parts of file and it will be combined automatically

- You can fix merge conlicts locally in nano by deleting stuff you don't want ">>> === <<<<"

