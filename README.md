Workflow
========

Guides and ideas of how we should use Github.
Feel free to play around with the demo-repository, following this guide.

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



Workflow in eclipse
===================

The following guide is supposed to explain how we work with the explained workflow in Eclipse.
You are pressumed to have installed the eGit plugin in eclipse.

It's the beginning of a sprint... Where do I start, you ask?
Well you want a fresh clone of the develop branch to continue work on.
In Eclipse, do the following steps:

file > import… > git > projects from git > URI > {the git address}

choose only the develop branch and keep clicking next in the following pop-ups.

You will now have the project in the package explorer in eclipse. 

![git view](images/git.png)

The text within brackets to the right of your project corresponds to [Repository Current_Branch].
Before you start working, you want to create a new branch for the feature you are implementing.

To do this, right click on your repository in the git view and choose switch to > new branch...

![create a new branch](images/cool-feature.png)

This is your working branch. For more info of how to use git in your work (commit, add etc.), RTFM ;)

Once you are ready for code review, you need to push your branch up to github.
To do this you simply right-click on your repository in the git view and choose "push to upstream"

Now your branch is on github and you want someone to review it and merge it with the develop branch.
Goto to the repository on github and choose pull request > create pull request.
Make sure the pull request you create concewrns YOUR branch and develop

![pull requests](images/pullreq.png)

Then click “send pull request”!
Now you are done!





