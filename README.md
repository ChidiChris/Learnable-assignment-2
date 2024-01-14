# Learnable-assignment-2

1. _Explain Version Control_:
   Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It allows multiple people to work on a project, knowing they can access versions of files from a specific point in time, revert to previous versions, and merge changes made by multiple people. This is especially crucial in software development and collaborating on projects.

2. _Difference Between Git and GitHub_:

- Git is a distributed version control system that allows you to keep track of your software at the source code level. It is a command-line tool that helps you manage and keep track of your source code history.
- GitHub, on the other hand, is a web-based platform that provides hosting for software development version control using Git. It adds a graphical interface and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

3. _Three Other GitHub Alternatives_:

- Bitbucket
- GitLab
- SourceForge

4. _Difference Between Git Fetch and Git Pull_:

- "git fetch" retrieves the latest changes from the remote repository but does not merge them into your current branch. It's useful for viewing the changes and necessary for situations where you need to inspect changes before downloading or merging them.
- "git pull" fetches the changes from the remote repository and merges/updates your current branch with the remote branch.

5. _Git Rebase_:
   In simple terms, git rebase is used to integrate the changes from one branch into another. It is often used to maintain a clean, linear project history. The command for it is:
   bash
   git rebase <branch_name>

6. _Git Cherry-Pick_:
   Cherry-pick is used to pick a single commit from one branch and apply it to another. It's useful if you need to apply a specific commit to a different branch. The command for it is:
   bash
   git cherry-pick <commit_hash>
