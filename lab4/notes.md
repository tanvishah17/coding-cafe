# Lab 4 Answers

## Question 1
global means “save this Git setting for my entire user account on this computer.” Git saved my name and email as the default author name for all Git repositories I use on my Mac. If we left global out, Git would normally save that setting only for that particular repository. With --global, you don’t have to configure your name and email separately in every repository.

## Question 2
.git appeared in ls -a but not in ls. It is hidden because its name starts with .. It is the directory Git uses to store the repository’s internal information, such as commits, branches, configuration, and tracking data.

## Question 3
Git is offering to track 4 items: .DS_Store, README.md, lab4/, and week02/. .DS_Store looks like something I did not write because macOS creates it automatically.

## Question 4
.venv/ and .DS_Store disappeared from the list because they are now included in .gitignore.

## Question 5
.gitignore should be committed, not ignored. It contains the rules that tell Git which files and folders to leave out of the repository, so other people working on the project also get the same ignore rules.

## Question 6
README.md moved from Untracked files to Changes to be committed. In the three-places model, it moved from the working directory to the staging area (index). Git is now prepared to include it in the next commit

## Question 7
Git created the first commit and reported 5 files changed, 88 insertions(+)

## Question 8
The first seven characters are a935e46. They are the shortened version of the commit’s unique commit hash (SHA), which identifies that specific commit.

## Question 9
## Question 10
## Question 11
## Question 12
## Question 13
## Question 14