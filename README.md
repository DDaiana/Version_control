
Version control with Git commands - first part of the lecture

git pull - pulls from the repo we are connected to 
git push - push our local changes out to be used by others who have access to the repo
git add. - stages any changes we have made ready to be comited
git commit -n "my message" - prepares our work ready to be uploaded to github
git status - shows status of whether files have been added or pushed or commited
git clone <address of repo> - makes a copy of the repo from github to your local environment 
git init - use to initialise a repo so we can start tracking it
git log - gives us a history of our comits so far
git remote add origin <address> creates a link between our pc and GitHubg
git push -u origin main - for our first push
//the flow: add -> push -> commit

//recovery commands
git reset --soft HEAD^ - undo your last commit, but the files & changes are still staged
git reset --mixed HEAD^ or git reset Head^ - undo your last commit and unsatge files and changes
git reset --hard HEAD^ - undo your last commit and delete all of its files and changes from the working tree; be careful when using it

Note! CI/CD - continous integration and continous development 

git branch - lets you create, list, rename, and delete branches
git checkout -b dev - adds a new branch called dev
git checkout main - switches to an existing branch
git push --set-upstream origin dev - this allows 
git diff <filename> - shows any differences between the files


Note! for additional information go to https://git-scm.com/docs 


Writing a README.md file guidelines - second part of the lecture 

Must have: 
- projefct title
- project description
- installation and usage
- technologies
- process 
- licence

Should have:
- screenshots/Images
- wins and challenges

Could have:
- badges
- contrbution guide
- code snippets
- bugs 
- future features

Note! additional information on writing on GitHub can be found at: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
additional information on adding badges can be found at:
https://github.com/badges/shields
make your own badges at: https://shields.io/#your-badge