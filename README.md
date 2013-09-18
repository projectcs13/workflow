Workflow
========

Guides and ideas of how we should use Github

Overview
========

Our repository will have three main branches: master, release and develop. 
You should never push any commits to these branches directly. 
Instead whenever you add a feature you create a new branch for this feature. 
Then, when you're done with the feature, you create a pull-request of this 
new branch in to develop. This is done using the Github homepage.

* master
* release
* develop
* sprintX.Y

Whenever you start working on a new feature, you create a new branch to work on.
The naming-convention of this branch is sprintX.Y where X is replaced by the current sprint
and Y is replaced by the new feature.

The basic workflow is comprised of the following steps:

* clone from github 
* create a new branch locally to work on 
* push to github when the branch is ready for review 
* create a pull request from branch to develop
* repeat
