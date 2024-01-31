# terminal git commands for maintaining repo on github

## Personal project (challenge work aka a code base where YOU are the only contributor):

- git clone

- git add .
- git commit -m "COMMIT MESSAGE GOES HERE"
- git push

## Group project (project work aka a code base where you are working with a team):

- git clone

- git checkout -b dev(DEV-NAME-GOES-HERE)

  - this will create a new branch which will be the branch you want to do ALL your work on.

- git add .
- git commit -m "COMMIT MESSAGE GOES HERE"

- git pull origin main

  - this step is where any possible merge conflicts will pop up.

- if no merge conflict then:

  - git push origin dev(DEV-NAME-GOES-HERE)

- if merge conflict then
  - resolve merge conflict (I reccomend taking care of this in vs code.)
    - git add .
    - git commit -m "resolve merge"
    - git push origin dev(DEV-NAME-GOES-HERE)
