## GIT comands

Команды для git, которые не легко запомнить

```
git log
git log --pretty=format:"%h - %an, %ar : %s"
git log -p -2
```
Другие команды
```
Link для kdiff3
http://kdiff3.sourceforge.net/
git config --global merge.tool kdiff3
git config --global mergetool.kdiff3.cmd '"w:\\Program Files\\KDiff3\\kdiff3" 1BASE 1LOCAL 1REMOTE -o 1MERGED'
git merge
git mergetool
```