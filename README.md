howtousegit
===========

*The slides for this repo will be uploaded soon...*

## CLI

* clone git repo: `$ git clone https://github.com/johannesboyne/howtousegit.git`
* *modify README.md*
* add modified: `$ git add README.md`
* commit: `$ git commit -m "README modified"`
* push: `$ git push`
* *remote repo has been updated*
* pull: `$ git pull`
* *merge conflict*
* `Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.`
* `$ git mergetool -t opendiff` (or `git mergetool`)
* ---
* new branch: `$ git branch hotfix`
* checkout new branch: `$ git checkout hotfix` or, shortform (creating and checkout): `$ git checkout -b hotfix`
* get status: `$ git status`
* add modified, commit: `$ git add README.md && git commit -m "changed README"`
* push local branch to remote repo: `$ git push -u origin hotfix`
* ---
* fetch remote branches: `$ git fetch`
* show all branches: `$ git branch -r`
* merge branches: `$ git merge origin/tower_hotfix` or if you pulled `$ git merge tower_hotfix`
* `$ git checkout master` `$ git merge hotfix` `$ git branch -d hotfix`
* deleting remote branch: `$ git push origin :hotfix`

## Git Tower

* clone git repo: ![Tower: clone repo](clone-remote-repo.png)
* *modify README.md* ![Tower: modified](modified-local.png)
* add modified: ![Tower: staging modified](staging-local.png)
* commit: ![Tower: commit staged](commit-local.png) ![Tower: commit staged](commit-local2.png) ![Tower: local-ahead now](local-ahead.png)
* push: ![Tower: push button](push-btn.png) ![Tower: push info](push-info.png)
* *remote repo has been updated*
* pull: ![Tower: git pull](git-pull.png)
* *merge conflict*
* ![Tower: merge conflict](merge-fail.png)
* ![Tower: open merge tool](open-merge-tool.png)
* ---
* new branch: ![Tower: new local branch](new-local-branch.png) ![Tower: new local branch](new-local-branch2.png)
* push local branch to remote repo: ![Tower: publish local branch](publish-local-branch.png)
* ---
* fetch remote branches: ![Tower: fetch remote branches](git-fetch.png)
* merge branches: ![Tower: merge branches](merge-branches-btn.png) ![Tower: merge branches](merge-branches.png)
* deleting branch: ![Tower: delete branch](delete-branch.png)
