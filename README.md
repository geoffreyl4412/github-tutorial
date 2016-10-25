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

**Adding and Commiting**  
After some edits on your README.md file, what you want to do is to add your changes to the staging area. Use `git add file`, to add a specific file to the stage, or `git add .`, which adds the current file you're in to the stage. You can still edit the file after adding to the stage, but **remember** to do `git add .` after!  
When you want to save, use `git commit -m "message"`. The message should be in the present tense and short, but long enough to explain what you did.


---
## Workflow & Commands