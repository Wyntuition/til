## Occassionally run:

`git gc --auto` 

Less frequently, you can run 

`git gc --aggressive`

It runs a variety of housekeeping tasks such as compressing file revisions & removing unreachable objects, to optimize diskspace and performance. 

https://git-scm.com/docs/git-gc 

## Also run, 

`alias git_clean='git branch --merged | grep -v "\*" | xargs -n 1 git branch -d’`

This will create an alias you can use to clean local branches. 