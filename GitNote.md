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

## add all files
- `git add *.txt`
- `git add *.*` or `git add .`

## add remote repository
- `git remote add origin "location of remote repo"`
    + `git remote add origin https://github.com/Mac-Y/Note.git`
- `git push -u origin master`
