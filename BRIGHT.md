How to update this repo

Add the offical repo as a remote
`git remote add SolidStateGroup git@github.com:SolidStateGroup/bullet-train-api.git`
Your remotes should now look like this:
```
git remote -v 
SolidStateGroup git@github.com:SolidStateGroup/bullet-train-api.git (fetch)
SolidStateGroup git@github.com:SolidStateGroup/bullet-train-api.git (push)
origin  git@github.com:brightinteractive/bullet-train-api.git (fetch)
origin  git@github.com:brightinteractive/bullet-train-api.git (push)
```

Fetch the latest changes
`git fetch SolidStateGroup`

Rebase our tweaks on top of the latest changes, fixing any conflicts
`git rebase SolidStateGroup/master`

Push your changes
`git push -f`

