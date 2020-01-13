How to update this repo

Add the offical repo as a remote
`git remote add BulletTrainHQ git@github.com:BulletTrainHQ/bullet-train-frontend.git`
Your remotes should now look like this:
```
git remote -v 
BulletTrainHQ	git@github.com:BulletTrainHQ/bullet-train-api.git (fetch)
BulletTrainHQ	git@github.com:BulletTrainHQ/bullet-train-api.git (push)
origin  git@github.com:brightinteractive/bullet-train-api.git (fetch)
origin  git@github.com:brightinteractive/bullet-train-api.git (push)
```

Fetch the latest changes
`git fetch BulletTrainHQ`

Rebase our tweaks on top of the latest changes, fixing any conflicts
`git rebase BulletTrainHQ/master`

Push your changes
`git push -f`

