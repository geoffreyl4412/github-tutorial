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



---
## Repository Setup
**Making the Repository:**  
To set up your repository, you first make your folder. Then you **must** `cd` into it. After you do this, use `git init` to initialize git for version control and now it's a repo! You can make a README.md file and type some things down.

**Adding and Committing**  
After some edits on your README.md file, you should probably add your changes. Use `git add file` or `git add .` to do that. You can still edit the file after adding, but **remember** to add it again after!  
When you want to save, use `git commit -m "message"`. This makes a save file that shows the changes made from what you did after the previous commit.

---
## Workflow & Commands