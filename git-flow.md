# Git Flow

Useful contents about Git Flow:

* Git Flow video (PT-BR): https://www.youtube.com/watch?v=oweffeS8TRc
* Git Flow hands-on video (PT-BR): https://www.youtube.com/watch?v=p1VAghNq-qg
* Git Flow article (PT-BR): https://medium.com/trainingcenter/utilizando-o-fluxo-git-flow-e63d5e0d5e04
* Git Flow cheatsheet (PT-BR): https://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html
* Git Flow workflow (EN): https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

Steps:

1. Install git-flow toolkit:

       sudo apt-get install git-flow

2. Initialize git-flow in the current Git repository. This command will ask you what names you would like to use in your branches:

       git flow init

3. Feature:

       1. Create a new feature branch to work in something new. This command will add a default prefix in your branch:

              git flow feature start <branch_name>

       2. Send your commits to a remote branch so that others can see it:

              git flow feature publish <branch_name>

       3. Update your local branch:

              git pull

       4. Finish a feature. 

              git flow feature finish <branch_name>

