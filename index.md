<img src="https://user-images.githubusercontent.com/84395267/120447628-69b00f00-c3a8-11eb-8ed1-17601e493b79.gif" width="150" height="150"/>

<b>CREATING REPOSITORY</b>
1. In upper right corner, next to your avatar or identicon, click + and then select new repository.
2. Name your repository myfirst-repo.
3. Write a short description.
4. Select initialize this repository with ReadME.
5. Click create repository.

 <b>CREATING BRANCH</b>
1. Go to your new repository myfirst-repo.
2. Click the drop down menu at the top of the file list that says branch:main.
3. Type a branch name, readme-edits, into the new branch text box.
4. Select the blue Create branch box or hit "Enter" on your keyboard.

<b>COMMIT CHANGES</b>
1. Click the README .md file.
2. Click the ✏️ icon in the upper right corner of the file view to edit.
3. In the editor, write something about project.
4. Write a commit message that describes your changes.
5. Click commit changes button.

<b>CREATE PULL REQUEST</b>
1. Click Pull Request tab, and click green New pull Request button.
2. In example comparison box, select branch you made, readme-edits, to compare with main(the original).
3. Look over your changes in the diffs on the compare page, make sure they're what you want to submit.
4. Click the big green Create Pull Request button.
5. Give your pull request a title and write a brief description of your changes.

<b>MERGE PULL REQUEST</b>
1. Click the green Merge Pull Request button to merge the changes into the main branch.
2. Click confirm merge.
3. Go ahead and delete the branch, with delete branch button in purple box.

### CONTRIBUTIONS
* Commiting to repository's default branch or gh-pages.
* Opening an issue
* Opening a discussion
* Answering a discussion
* Proposing pull request
* Submitting pull request review

<b>GITHUB FLOW</b>
 
*It is light weight, branch-based workflow that supprts teams and projects where deployements are made regularly. When you **create a branch** in project, you're creating an environment where you try out new ideas. Changes you make on a branch dont affect main branch, so you are free to experiment and commit changes, safe in the knowledge that your branch won't be merged until it's ready to be reviewed by someone you're **collaborating** with.Your branch name should be descriptive because it is created off main when working on a **feature** or **fix**.*

<b>GIT HANDBOOK</b>

_Version control system tracks (**VCS**) history of change as people and teams collaborate on projects together. As the project envolves, teams can **run tests**, **fix bugs**, and **contribute new code** with the confidence that any version can be recovered at any time. Developers can also **review project history** to find..._
*  Which changes were made?
*  Who made the changes?
*  When were the changes made?
*  Why were the changes needed?

_Distributed Version control system (**DVCs**) is commonly used for **open source** and **commercial software** development. They allow access to every file, branch and iteration of project, and allow every user access to full and self-contaimed **history** of all changes. Developers can work anywhere and collaborate asynchronously from any time zone._

**BASIC GIT COMMANDS**

* git init - initialize brand new repository
* git clone - create local copy of project
* git add - adding files to snapshot
* git commit - saving the snapshot
* git status - show status of changes
* git branch - show branch worked locally
* git merge - merge line of development
* git pull - update local line of development
* git push - update repository with commits   
 
## HOW GITHUB WORK

_GitHub builds collaboration directly into thye developmenmt process. Work is organized into repositories, where developers can outline requirements or directions and set expectations for team members. Developers simply create a branch to work on updates, commit changes to save them, open a pull request to propose and discuss changes, and merge pull requests once everyone is on same page._

________________________________________________________________________________________________________________________________________________________________________________

* Contribute to an existing repository

1. git clone https://github.com/me/repo.git
2. cd repo
3. git branch my-branch
4. git checkout my-branch
5. git add file1.md file2.md
6. git commit -m "my snapshot"
7. git push --set-upstream origin my-branch

* Start new repository and publish it on GitHub

1. git init my-repo
2. cd my-repo
3. touch README.md
4. git add README.md
5. git commit -m "add README to initial commit"
6. git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
7. git push --set-upstream origin main

* Contribute to existing branch on GitHub

1. cd repo
2. git pull
3. git checkout feature -a
4. git add file1.md
5. git commit -m "edit file 1"
6. git push
________________________________________________________________________________________________________________________________________________________________________________
