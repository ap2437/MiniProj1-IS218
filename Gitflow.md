<h1>Gitflow</h1>	


The gitFlow workflow consists of alterations to pre-existing features. 
First, a develop branch must be created because that is where the more important feature branch will come from. 
Once a feature has been completed, it’s content merges back into the develop branch.
Once the merge is finished, a release branch is created off of develop. The release goes through a series of testing and debugging until the developers are pleased with the result.
Once the release is finished, the branch merges with master and also develop to ensure the information doesn’t get overwritten. 
Hotfix branches were introduced to get quick patches out. Unlike release, hotfix is based off of master. Once the quick fix is made, the hotfix branch should be merged with both master and develop this way it isn’t lost during the next release.
