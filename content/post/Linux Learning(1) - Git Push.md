+++
date = "2021-07-14T12:00:00-00:00"
title = "Linux Learning(1) - Git Push"
tags = [ "Linux Learning" ]
comments = true
share = true
+++
## What is Hugo?


#### To push changes of website from .md to github through git
First time:
```
1. git init
2. git add .
3. git status
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin https://github.com/ireneyrzd/Homepage.git
7. git push -u origin main
```
After origin and main has been initialized:

```
1. git status
2. git add <file>
3. git rm <file>
4. git status
5. git commit -m "commit comment"
6. git push -u
```
#### View local host website
```
1. hugo server -D
```
