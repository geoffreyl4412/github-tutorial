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