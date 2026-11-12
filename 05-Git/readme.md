Git – Learning Journal
Overview
Git is a distributed version control system used to track changes in files and manage a project's development history. It allows developers to work locally, maintain earlier versions and combine work from different branches.
What I Learned
1. Version Control
I learned why version control is important for tracking modifications, identifying who made changes, recovering earlier versions and coordinating work among multiple contributors. I also explored local, centralized and distributed version control systems.
2. Introduction to Git and Its Architecture
I understood that Git maintains project history through commits and supports parallel development using branches. I learned about the working directory, local repository and remote repository, and how they are connected.
3. Repositories and the Basic Workflow
I learned how to initialize a repository and how Git organises work into three main areas:
- Working directory: Files that are being edited.
- Staging area: Changes selected for the next commit.
- Repository: The committed project history.
The basic workflow is:
Edit → Stage → Commit → Push
4. Essential Git Commands
I practised commands for managing and inspecting a repository, including:
Command	Purpose
git init	Initialize a repository
git status	Check the state of files
git add	Stage changes
git commit	Record staged changes
git log	View commit history
git diff	Compare changes
git ls-files	List files known to Git
git mv / git rm	Rename or remove tracked files


I also learned how .gitignore prevents selected files, such as caches, local configuration and generated files, from being tracked.
5. Managing and Undoing Changes
I explored how to unstage changes, discard unstaged modifications and safely reverse a previous commit. In particular, I learned the difference between git restore and git revert: restoring can discard local edits, while reverting creates a new commit that reverses an earlier commit.
6. Branching and Merging
I learned how branches allow independent development without directly changing the main line of work. I explored creating, listing and switching branches, merging changes and resolving merge conflicts when Git cannot combine edits automatically.
Key Takeaways
This topic helped me understand how Git keeps a structured history of a project. I learned to track changes through staging and commits, inspect earlier work, manage branches and handle mistakes or merge conflicts. I also understood why meaningful commit messages and regular reviews are important for maintaining a clean project history.
