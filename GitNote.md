# Git Note

## add github email and username to git
- `git config --global user.email "yerongqi1986@gmail.com"`
- `git config --global user.name "Mac-Y"`

## imoortant Commands
- `git --version`
- `git init` (when in the location of the folder/project)
- `git status`
- `git add`
- `git commit -m "message you want to write"`
    + `git commit -m "added file"`
- `git log`
- `git --help`

## add all files
- `git add *.txt`
- `git add *.*` or `git add .`

## add remote repository
- `git remote add origin "location of remote repo"`
    + `git remote add origin https://github.com/Mac-Y/Note.git`
- `git push -u origin master`
    + `git push [remote-name] [branch-name]`

## branching and merging
- `git branch "your branch name"`
- `git checkout "your branch name"`
- `git merge "your branch name"` (merge your branch in master branch, when you in the location of master)
- `git branch -d "your branch name"` (delete from local)
- `git push origin --delete "your branch name"` (delete from remote)
