![image](https://github.com/ADATYA/Git-Tutorials/assets/97549431/d2ae1d5a-c71c-4bea-9b34-891eabbb3ce4)


# Git-Tutorials
### Version control: 
Git excels at tracking changes to your files over time. This allows you to:
* Revert to previous versions: 
If you make a mistake or want to see how your project looked earlier, you can easily revert to a specific point in time.
* See the history of changes: 
You can understand how your project has evolved by viewing the history of commits, which are snapshots of your project at specific points in time.
### Collaboration:
  Git is a powerful tool for collaborating with others on projects.It enables:
* Multiple people to work on the same project simultaneously: 
Each team member can work on their own branch without interfering with others' work.
* Merging changes seamlessly:
When everyone is ready, their changes can be merged into the main codebase easily.

## Additional benefits:

* Branching: 
Git's branching feature allows you to experiment with different ideas or features without affecting the main codebase. This is crucial for maintaining stability while working on new developments.
* Offline availability: 
You can use Git even without an internet connection, making it suitable for working on projects while traveling or in areas with limited internet access.
* Widely adopted: 
Git is the most popular version control system, making it the industry standard for many software development projects. This widespread adoption means there are numerous resources and communities available to help you learn and troubleshoot any issues you encounter.

# PDF of git cheat sheet:
[git-cheat-sheet-education.pdf](https://github.com/ADATYA/Git-Tutorials/files/14463957/git-cheat-sheet-education.pdf)

![image](https://github.com/ADATYA/Git-Tutorials/assets/97549431/6251b8a8-0ae9-4939-a0e7-212010f19361)


# Git Command :

* git config --global user name "your name"
* git config --global user email "your mail Id"
* git config --list


* git init
* git status
* git add "file name"  [ stage and ]
* git add . [add all]
* git re --cached <file> [to unstage]


* git commit -m "Type your comment"
* git log   [Details translation]
* git log --oneline

* git checkout 164e915 index.js   [Go to the previous head]   (<b>Syntex: git checkout "unique Id name" "file name")
* git unstage "file name"

# Ofline git reposetory command:

### Initialization:

* git init: Creates a new Git repository in the current directory.
Staging and Committing:

* git add 'file': Adds a specific file to the staging area for the next commit.
* git add .: Adds all tracked files in the working directory to the staging area.
* git commit -m "message": Creates a new commit with the specified message, permanently recording the changes in the staging area.
### Viewing Changes:

* git status: Shows the status of your working directory and staging area, indicating which files are modified, staged, or untracked.
* git diff: Shows the difference between your working directory and the index or another commit.
* git log: Shows the commit history of your repository, including commit messages, author information, and commit hashes.
### Branching and Merging:

* git branch 'branch_name': Creates a new branch.
* git checkout 'branch_name': Switches to a different branch.
* git merge 'branch_name': Merges another branch into the current branch.
### Other Useful Commands:

* git clone 'url': Clones an existing Git repository from a remote server (requires internet access).
* git remote add 'name' 'url': Adds a remote repository to your local repository (requires internet access).
* git config --global 'key' 'value': Sets a global Git configuration option.
* git help 'command': Provides help and documentation for a specific Git command.


  
# online git repository list with link
* GitHub: https://github.com/
* GitLab: https://about.gitlab.com/
* Bitbucket: https://bitbucket.org/product


