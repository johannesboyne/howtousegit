howtousegit
===========

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
* git 

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
