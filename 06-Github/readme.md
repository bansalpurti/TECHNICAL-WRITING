GitHub – Learning Journal
Overview
GitHub is an online hosting and collaboration platform for Git repositories. It allows developers to publish and share projects, review code and coordinate work with other contributors.

Git and GitHub are related but different: Git manages version history, while GitHub hosts Git repositories and provides online collaboration features.
What I Learned
1. Introduction to GitHub
I learned how GitHub is used to host source code, maintain project history, collaborate with developers, review proposed changes through pull requests and track tasks using Issues.
2. Exploring the GitHub Interface
I explored the main sections of a GitHub repository:
- Code: Project files and directories.
- Issues: Bug reports and task discussions.
- Pull requests: Proposed changes and code reviews.
- Actions: Automated workflows and testing.
- Settings: Repository permissions and configuration.
3. Creating an Account and Repository
I learned the basic steps for creating a GitHub account and setting up a repository. I also understood the difference between repository visibility options:
- Public: Anyone can view the repository.
- Private: Access is limited to authorised users.
4. Connecting Git with GitHub
I learned how a local Git repository can be connected to a remote GitHub repository. I explored the role of a remote (commonly named origin) and how commits can be pushed to GitHub.

I also learned how cloning creates a local copy of a remote repository, including its files and history.
5. Synchronising Changes
I explored the commands used to exchange changes between local and remote repositories:
Command	Purpose
git remote add origin URL	Connect a local repository to a remote
git push	Upload local commits
git fetch	Download remote updates without integrating them
git pull	Fetch and integrate remote updates
git clone URL	Create a local copy of a remote repository


6. Collaboration Through Branches and Pull Requests
I learned how developers can work on separate feature branches, push their work to GitHub and open pull requests for review. After reviewing the proposed changes, the pull request can be merged into the main branch.

The collaborative workflow is:

Create Branch → Commit Changes → Push Branch → Open Pull Request → Review → Merge
7. Authentication and Security
I learned about connecting to GitHub using HTTPS or SSH and the importance of protecting credentials. Passwords, personal access tokens, private SSH keys and API keys should never be shared or committed to a repository. I also understood that .gitignore does not remove a secret that has already been committed to Git history.


Key Takeaways
Through this topic, I understood how GitHub extends Git by making repositories accessible online and supporting collaboration. I learned how to create repositories, connect local work to remote repositories, clone and synchronise projects, and use branches and pull requests for code review. I also became aware of the importance of repository permissions and credential security.
