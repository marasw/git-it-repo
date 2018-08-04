Create a (feature)branch
Branching and merging is what makes Git so powerful and for what it has been optimized, being a distributed version control system (VCS). Indeed, feature branches are quite popular to be used with Git. Feature branches are created for every new kind of functionality you’re going to add to your system and they are normally deleted afterwards once the feature is merged back into the main integration branch (normally the master branch). The advantage is that you can experiment with new functionality in a separated, isolated “playground” and quickly switch back and forth to the original “master” branch when needed. Moreover, it can be easily discarded again (in case it is not needed) by simply dropping the feature branch. There’s a nice article on understanding branches in Git which you should definitely read.

But lets get started. First of all I create the new feature branch:

$ git branch my-feature-branch
Executing

$ git branch
* master
  my-feature-branch