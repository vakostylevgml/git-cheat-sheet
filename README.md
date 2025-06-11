# git-cheat-sheet

## Installation

- [Download Git for all platfoms] (htp://git-scm.com)
or for specific platform 
- [For Mac] (htps://windows.github.com)
- [For Windows] (htps://windows.github.com)

## Setup 

1. Configure user information
```
git config --global user.name “[firstname lastname]”
git config --global user.email “[valid-email]”
```

2. Init repository 
New local repository:
```
git init
```
Or clone existing
```
git clone [url]
```

## Basic usage
Show repository status
```
git status
```
Add file 
```
git add file.extension
```
Commit file 
```
git commit -m "commit msg"
```
Push to remote repository
```
git push origin master
```

## Git log

Used to show commit history.

To show compact view of log use:
```
git log --oneline
```

