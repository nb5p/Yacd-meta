# DO NOT USE THIS REPO

### Some Cheat Sheet for Me

> Q: How to create PR?
> 
> ```shell
> git checkout --orphan=<BRANCH_NAME>
> git rm -rf .
> git remote add upstream git@github.com:MetaCubeX/Yacd-meta.git
> git fetch upstream
> git merge upstream/master
>
> # change and commit here
> 
> git push origin <BRANCH_NAME>:master -f
> ```
