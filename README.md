picshare
========

This repository is the common part of the 3 team taking part in the API13 project called "Picshare" from the UTC.

Clone this repository:
----------------------
* If you use SSH with git simply do : `git clone git@github.com:garciafl/picshare.git`
* Then inside the repository do : `git submodule init; git submodule update`
* The submodules should now be correctly set.

Configure eclipse (to improve and test):
----------------------------------------
* Choose import project from existing sources with the picshare folder
* Add libraries from the lib folder to your classpath

Update a repository
-------------------
* `git fetch --all`
* `git pull`

Commit
------

You can't commit on this repository. Do the changes in the submodules (juste move to the right folder and change files).

<b>Remember that you should never commit on master</b>. Create a new branch for every modification.

Process to add a modification
-----------------------------

* go on master branch: `git checkout master``
* create a new branch: `git branch "NAME OF YOUR BRANCH`
* switch to your new branch: `git checkout "NAME OF YOUR BRANCH`
* once your modifications are done do: `git add -p` to validate your modification
* then commit: `git commit -m "My message commit"``
* you can do more than one commit and then: `git push origin <LOCALBRANCHNAME>:<REMOTEBRANCHNAME>`
* then go to github and create the pull request

For more information on git you can take a look at :
[Github best practices](http://codeinthehole.com/writing/pull-requests-and-other-good-practices-for-teams-using-github/)
