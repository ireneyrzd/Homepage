+++
date = "2021-07-25T12:00:00-00:00"
title = "Linux Learning(2) - Hugo and Git Rebase"
tags = [ "Linux Learning" ]
comments = true
share = true
+++
## What is Hugo?
Hugo provides sample website templates, which include intructions in simple English language in how to fill in different sections. Once that is complete, Hugo will automatically generate the html code for the website using the template. The website can then be published using a url domain such as one from github.

#### How?**
Once template has been filled out, the static page can be build using code below:

First time: make sure a folder has been created to store the generated HTML code. A new repo can be created following the instruction in my earlier post (Git Learning(1))

To update to the folder:
```
hugo -d ../ireneyrzd.github.io/
cd ../ireneyrzd.github.io/

git add .
git status
git commit -m "commit comment"
git push
```

** How to download template: https://gohugo.io/getting-started/quick-start/

## Git rebase
#### Why?
To pull commits from remote to local, re-settup the basepoint of the local workspace to the newest commit, then resolve the conflict between the two versions.
#### Command
1). Git fetch
```
git fetch https://github.com/ireneyrzd/Homepage.git
or
git fetch origin
```
We use *fetch* instead of *clone* because we do not wish a new folder to be made in local finder, or *pull* because pull is equal to *git fetch + git merge*. Instead, we want it pulled to the local origin. I will further elaborate upon the differences between git fetch and git pull in a future post.

2). Git rebase
```
git rebase origin/main
```
3). Resolve conflict
After rebasing, the terminal will show:
```
Auto-merging config.toml
CONFLICT (content): Merge conflict in config.toml
error: could not apply 4007edc... Change Fav Holiday
Resolve all conflicts manually, mark them as resolved with
"git add/rm <conflicted_files>", then run "git rebase --continue".
You can instead skip this commit: run "git rebase --skip".
To abort and get back to the state before "git rebase", run "git rebase --abort".
```
Open the files with conflicting changes in a text editor, choose whether to keep "Their changes" or "My changes".
Once finished, run
```
git add/rm  <conflicted_files>
git rebase --continue
```
4). To check that rebasing worked, review:
```
git log
```
5). Finally, commit the changes, and push to github rep, and the website is generated at Settings/Pages
```
git status
git push
```

### Check origin
```
git remote get-url origin
```
