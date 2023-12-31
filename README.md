# LearningGit: These are my notes on how to use github the easy way
This is a repository to learn github in advance!

## Roadmap

* Updated Readme information
* Updated Counter Page
* 

## Steps for a new project

1. Create a new Github repository (it can be private or public)
1. add a readme file to it
1. add a gitignore file if you want. I add a visual studio ignore file so git does not push extra files to the source code
1. add a license if you need to the repository as it is an open source code
1. copy the https link for the repo so you can clone it in VS
1. make sure git is installed now on the machine
1. right click on folder where you want the VS to create the project. Git Bash here
1. Enter: git clone "paste url here"
1. cd "folder name"
1. git status
1. open Visual Studio and create new project. It can be blank if you want
1. enter the same repo name in the project/solution name when creating it
1. once created, open VS. Make sure you have Git Changes window open on the sidebar along with Solution Explorer
1. once the solution is made, we can push one change and commit it to github
1. 2 ways to do it. from Git Changes tab or Git BASH window
1. git add . / OR / VS: right click and stage
1. git commit -m "title message about the change" / OR / VS: enter message and commit staged
1. OPTIONAL: git status, git fetch, git pull / OR / VS: fetch, pull
1. git push / OR / VS: Push or Sync to do it all in one go

## New Branch / Switch Branch

1. git switch -c "new-branch-name" / OR / VS: 3 dots, new branch, name and done
1. check git status to confirm you are in new branch
1. git switch new-branch-name / main - changes to specified branch

## git commands

* git clone "url"
* git status
* git add .
* git commit -m "title message"
* git fetch
* git pull
* git push
* git switch -c "new-branch-name"
* git switch new-branch-name / main
* git branch (list of branches)
* git branch -d branch-name / git branch -D branch-name
* git tag -s "version" -m "release title message"
* git tag (list of tags)
* git push origin --tags (push tags to server from local)

## git functions to use

* issues: create issues, set assignee like in a ticketing system, add comments, close issues, etc.
* release/pre-release: versions, tags, version names, etc.
