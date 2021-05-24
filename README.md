# hello-world
Github Working 

**Create Repository**
A repository is usually used to organize a single project.It can contain folders and files, images, videos, spreadsheets, and data sets-anything your project needs.
We should include README ,a file with information about your project.It makes easy to add one at a same time you create a new repository.
**Steps**
1.In the upper right corner, next to your avatar, click + and then select new repository.
2.Name your repository hello-world.
3.Write a short description.
4.Select initialze this repository with a README.
5.Click create repository.

---------------------------------------------------------------------------------------------------------------------------------------------------

**Create Branch**
Branching is a way to work on differnt versions of a repository at a time.By default,our repository has one branch called main.
We use branches to experiment and make edits before committing to main.When you create branch of main, you're making a copy,or snapshot of main as it was at that point.
If someone else made changes to the main branch while you were working on your branch, you could pull in those updates.
**Steps**
1.Go to your new repository hello-world.
2.Click the drop down at the top of file list that says branch:main.
3.Type a branch name, readme-edits ,into the new branch text box.
4.Select the blue create branch box or hit "Enter" on keyboard.
5.Now you have 2 branches, main and readme-edits.

---------------------------------------------------------------------------------------------------------------------------------------------------

**Make and Commit Changes**
Commits are saved changes in github.Each commit has associated commit message, which is a description explaining why a particular change was made.
Commits message capture the history of your changes, so other contributors can understand what you've done and why.
**Steps**
1.Click the README.md file.
2.Click the pencil icon in the upper right corner of the file view to edit.
3.In the editor, write a bit about yourself.
4.Write a commit message that describes your changes.
5.Click commit changes button.

---------------------------------------------------------------------------------------------------------------------------------------------------

**Open pull Request**
Pull requests are heart of collaboration.When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into thier branch.
Pull Requests show differences ,of the content from both branches.The changes ,additions and subtractions are shown in green and red.
As soon as you make a commit, you can open a pull request and start a discussion ,even before the code is finished.
By using @mention system in your pull request message, you can ask for feedback from specific people or teams.
**Steps**
1.Click the pull request tab, then from the pull request page, click the green New Pull Request button.
2.In the Example Comparison box,select the branch you made, readme-edits to compare with main.
3.Look over your changes in the diffs on the Compare Page, make sure they're what you want to submit.
4.When you're satisfied that these are the changes you want to submit, click the big green Create Pull Request button.
5.Give your pull request a title and write a brief description of your changes.
5.When you're done with this message, click Create Pull Request(You can drop images and use emojis and gifs into comments and pull requests).

-------------------------------------------------------------------------------------------------------------------------------------------------

**Merge your Pull Request**
It's time to bring your changes together, merging your readme-edits into branch main.
**Steps**
1.Click the green Merge Pull Request button to merge the changes into main branch.
2.Click Confirm merge.
3.Go ahead and Delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.

--------------------------------------------------------------------------------------------------------------------------------------

**Understanding The Github Flow**
Github flow is a light weight, branch-based workflow that supports teams and projects where deployements are made regularly.
**Create a branch**
When you're working on a projkect, you're going to have a bunch of different ideas or features in progress at any given time-some of which are ready to go and some of which are not.Branching exists to help you manage this workflow.When you create a branch in your project, you're creating an environment where you can try out new ideas.Changes you make on a branch don't affect main branch,so you're free to experiment and commit changes ,safe in the knowledge that your branch won't be merged until it's ready to be reviewd by someone you're collaborating with.
**ProTip**
Branching is a core concept in Git, and the entire Github flow is based upon on it. There's only one rule:anything in main branch is always deployable.Because of this, it's extremely important that your new branch is created off of main when working on a feature of fix. Your branch name should be descriptive, so that others can see what is being worked on.

--------------------------------------------------------------------------------------------------------------------------------------

**Git Handbook**

**What is a Version Control System**
A version control system tracks the history of change as people and teams collaborate on projects together. As the project envolves , teams can run tests, fix bugs, and contribute new code with the confidence that any version can be **recovered** at any time.
Developers can review project history to find out.**Which changes were made? Who made the changes? When were the changes made? Why were the changes needed? **
______________________________________________________________________________________________________________________________________________________________________

**What is a Distributed Version Control System**
Git is an example of a distributed version control system, commonly used for open source and commercial software development. They allow full access to every file, branch, and iteration of a project and allows every user access to a full and self-contained history of all changes. Unlike once popular centralized version control systems, DVC'S like Git don't need a constant connection to a central repository. Developers can work anywhere and collaborate asynchronously from any time zone.

Without version control, team members are subject to redundant tasks, slower timelines, and multiple copies of a single project.To eliminate unnecessary work, Git and other VCSs give each contributor a unified and consistent view of a project surfacing work that's already in progress.Seeing a transparent history of changes, who made them, and how they contribute to the development of a project helps team members stay aligned while working independently.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Why Git?**
According to the latest stack overflow developer survey, more than 70% of developers use Git, making it most used VCS in the world. Github is commonly used for both open source and commercial software development,with significant benefits for individuals, teams and businesses.
________________________________________________________________________________________________________________________________________________________________________________
Git lets developers see the entire timeline of thier changes, decisions, and progression of any project in one place. From the moment they access the history of a project, the developer has all thr context they need to understand it and start contributing.
_________________________________________________________________________________________________________________________________________________________________________________
Developers work in every time zone. With DVCs like Git, collaboration can happen at any time while maintaining source code integrity.Using branches, developers can safely propose the changes to production code.
_________________________________________________________________________________________________________________________________________________________________________________
Businesses using Git can break down communication barriers between teams and keep them focued  on doing thier best teamn work. Plus, Git makes it possible to align texts across a business to collaborate on major projects.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Basic GIT Commands**
To use Git, developers use specifically commands to copy, create, change and combine code. These commands can be executed directly from command line by using an application like Github Desktop or Git Kraken. Here are some common commands for using Git.
_________________________________________________________________________________________________________________________________________________________________________________
Git init intializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.
_________________________________________________________________________________________________________________________________________________________________________________
Git clone creates a local copy of a project that already exists remotely.The clone includes all the project files , history and branches.
_________________________________________________________________________________________________________________________________________________________________________________
Git add stages a chance. Git track changes to a developer's codebase, but it's necessary to stage and take a snapshot of these changesto include them in the project's history. This command performs staging, the first part of that two step process. Any changes that are staged will become a part of the next snapshot and a part of tthe project's history. Staging and committing separately gives developers complete control over the history of thier project without changing how they code and work.
_________________________________________________________________________________________________________________________________________________________________________________
Git commit saves the snapshot to the project history and complete the change-tracking process. In short, a commit functions like taking a photo. Anything that's been staged with git add will become a part of the snapshot with git commit.
_________________________________________________________________________________________________________________________________________________________________________________
Git status shows the status of changes as untracked, modified,or staged.
_________________________________________________________________________________________________________________________________________________________________________________
Git branch shows the branch of being worked on locally.
_________________________________________________________________________________________________________________________________________________________________________________
Git merge merges line of development together.This command is typically used to combine changes made on two distinct branches.For example:a developer would merge merge when they want to combine changes from a feature branch into the main branch for deployement.
_________________________________________________________________________________________________________________________________________________________________________________
Git pull updates the local line of development with update from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in the local environment.
_________________________________________________________________________________________________________________________________________________________________________________
Git push updates the remote repository with any commits made locally to a branch.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**HOW GITHUB WORKS**
GitHub builds a collaboration directly into the development process. Work is organized into repositories, where developers can outline requirements or directions and set expectation for team members. Then, using the Github flow, developers simply create a branch to work on updates, commit changes to save them, open a pull request to propose and discuss changes, merge pull requests once everyone is on same page.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
