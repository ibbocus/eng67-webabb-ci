# webapp_intro_ci
## SDLC - One year for production 

## Web Hook
web-hook is a an inverted api call, a location in the app where you receive calls to changes 
location to receive an API call 


## What is a CI/CD Pipeline?
- CI/CD pipeline automates your software delivery process
- The pipeline builds code, runs tests (CI), and safely deploys a new version of the application (CD).
- Automated pipelines remove manual errors, provide standardised feedback loops to developers, and enable fast product iterations.

## Master Branch and Develop Branch Breakdown
A Project invovles a minimum of two branches to record the history of a project, the ```Master``` and ```Develop``` Branch.
The master branch stores the official release history, whereas the develop serves as an integration branch for features. 

The master branch at origin should be familiar to every Git user. Parallel to the master branch, another branch exists 
called develop.

The origin/master is considered to be the main branch where the source code of HEAD always reflects a ```production-ready state.```

The origin/develop is considered to be the main branch where the source code of HEAD always reflects a ```state with the latest 
delivered development changes for the next release```, also known as the“integration branch”. 

When the source code in the develop branch reaches a stable point and is ready to be released, all of the changes 
should be merged back into master somehow and then tagged with a release number

10

