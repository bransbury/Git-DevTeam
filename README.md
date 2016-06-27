# Git-DevTeam

A guide to using Git in a team environment.  

## Principles
* There are 2 permanent branches ([why?](#two-branches)): 
  * <b>'integration'</b> (where features are merged)
  * <b>'master'</b> (the current stable version)
* Commit early and often (why?)
* Push to the remote at least once per day (why?)

## Process

### :one: Branches


<b>Integration</b> is where multiple developers merge their code to.
This gives you a place:
* to view completed work not in production 
* to merge pull requests 
* to create a new product release from

### :two: Starting new work 
For normal work: <br/>
Create a new *'feature/bug/chore-[name]'* branch from <b>integration</b>
e.g. 'chore-update-dependencies', or feature-login-form

For a quick and urgent production fix <br/> 
Create a new *'hotfix-[name]'* branch from <b>master</b>

### :three: Finishing work 


## Personalize

## FAQs
#### <a name="two-branches">Why two permanent branches? </a>
<b>Master</b> is the stable production version.
This gives you a place: 
* to debug a production issue
* to branch off to do a [hotfix](# hotfix)
* to run your CI/build/deploy process
