# GitHub Tutorial

_by Geoffrey Lam_

---
## Git vs. GitHub
Git and github are may have similar names, but they are two _very_ different things. In git, many people can clone or fork the same project and modify it. In github, code gets stored into the cloud. The differences are listed below:

**Git**
* Uses version control
* User friendly
* Internet isn't needed
* Doesn't require Github

**Github**
* Others can work on the same file
* Can easily see commits made
* Internet is needed and is public
* Requires Github

---
## Initial Setup
To get started, make a github account using your hstat email. Then, go to cloud9 and connect github to it. After that, you make a new workspace, fill out the info on it, and then create it.  
In order to create an SSH key 


---
## Repository Setup
**Making the Repository:**  
To set up your repository, you first make your folder. Then you **must** `cd` into it. After you do this, use `git init` to initialize git for version control and now it's a repo! You can make a README.md file and type some things down.

**Adding and Committing**  
After some edits on your README.md file, you should probably add your changes. Use `git add file` or `git add .` to do that. You can still edit the file after adding, but **remember** to add it again after!  
When you want to save, use `git commit -m "message"`. This makes a save file that shows the changes made from what you did after the previous commit.

**Remote Repo on Github**  
To keep track of your commits, you have to make a remote repo on your github. After setting up your account and creating the SSH key, go and make a new repo on github. From there, the repo name **has** to be the same name as the repo you want to `push` into. After creating the repo, you should copy and paste the code for _pushing into an existing repository_ in SSH one at a time. The first one enables the repos to be connected. The second one brings your changes up to the remote repo. Now you can push your changes to your remote!

---
## Workflow & Commands
`git status` is very helpful because it checks to see what you've edited and what you've added to the stage. You can (and should) always use this command if you're not sure if you've added or committed yet.  
`git add` adds the selected file into the staging area. This file can still be edited, as it has not been saved yet, but remember to add it back later. You should **always** use `git add` whenever you make a change to a file.  
`git commit` saves the selected file. This allows you to look back at what you've modified when you view your past commits. You should use this command whenever you are ready to save and after `git add`. If you don't do `git add`, there would be nothing to save or commit.  
`git push` brings the commits you've made from the local repo to the remote repo. This is very useful, as others might want to fork or clone your repo, or you lose your local repo. The things you've made in th local should be in the remote, as long as you `push` those changes. Use this command whenever you've committed so that the most recent change gets brought up.