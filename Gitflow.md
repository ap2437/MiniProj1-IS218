<h1>Gitflow</h1>	

<ul>
<li><p>The gitFlow workflow consists of alterations to pre-existing features.<p></li>
<li><p>First, a develop branch must be created because that is where the more important feature branch will come from. <p>
</li>
<li><p>Once a feature has been completed, it’s content merges back into the develop branch.<p></li>
<li><p>Once the merge is finished, a release branch is created off of develop. The release goes through a series of testing and debugging until the developers are pleased with the result.<p></li>
<li><p>Once the release is finished, the branch merges with master and also develop to ensure the information doesn’t get overwritten. <p> </li>
<li><p>Hotfix branches were introduced to get quick patches out. Unlike release, hotfix is based off of master. Once the quick fix is made, the hotfix branch should be merged with both master and develop this way it isn’t lost during the next release.<p></li>
  
</ul>



More information about Gitflow is available here [Gitflow](https://datasift.github.io/gitflow/IntroducingGitFlow.html#:~:text=GitFlow%20is%20a%20branching%20model,and%20scaling%20the%20development%20team.).
![GitFlow](https://wpdevkvk.files.wordpress.com/2017/03/diagram.png?resize=900%2C506)
