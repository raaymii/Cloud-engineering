Instructor: Gill Cleeren

----AN OVERVIEW OF GIT AND GITHUB----
GIT AND GITHUB
Git is a source control system, a very popular one and very widely adopted one as well. It allows many users, even distributed, to work on small and large software projects in a very simple, yet powerful way.
Git is a distributed source management system.
It was created by Linus Torvalds and it is open-source and free.

Why use Git?
-It is fast, really fast and scalable
-It can also work disconnected
-It is powerful, yet easy to use
-Using branches is another benefit of Git. The main branch always contain quality code.
-Pull requesets: It enables collaborating on code. Using pull requests, a developer can ask for a review and merge back into another branch of the changes that he/she has performed.

Challenges with working with Git
-It is different. It has multiple local levels and a remote typically
-Developers working with Github also complain about the learning curve they have to go up when learning to work with Git.
-Tools
-Large binary files

What is Github?
Github is a Git-hosting site. It provides a hosting service for Git repositories, and it's used by many developers for personal projects as well as numerous companies around the globe for small and large software projects.
It offers issues management, working with teams, adding a wiki and so much more. It is more than just source control for your code.
Github offers a free tier, as well as paid options

Foundations of Git
Centralized Source Code Management: In a centralized source code management system, we have a central copy of the source on a server. That central server is the main repository, and it contains all versions of the code. When we want to make changes on the code, we first need to copy the code from the server. This will get the current version of the code down, and that will give you a local copy of that code. When I make changes to the code and that would then be committed again back to the central repository.
In the centralized system, we work with changesets.
A changeset is a number of changes that is treated as a whole.
In the distributed system, a developer will clone the entire repository and therefore get the entire history on their machine. This way of working doesn't require a central store, although typically, there will be one. In that case, the central store will be Github.
The process of sending information back to the repository is pushing.

The 3 states of Git
-Committed: the data is basically stored in the local database.
-Modified: this state means that the file has been changed, but it hasn't been committed to the database yet.
-Staged: this state means that the modified file is marked to be part of the next commit snapshot.
All these changes are still local.

The 3 areas of Git
-Working directory: this is where the content will be created, edited and deleted. Typically, for the existed files, these files will be extracted from the local Git database.
-Staging directory: it can be seen as the area where changes from the local directory will be staged before they are committed. When files are in the staging area, they are waiting to be committed typically. They will be probably part of the next commit.
-Git directory(.git repo): once a commit is performed, all changes will be stored in the local Git directory. This is also created when we clone source from another computer or from Github.
-Remote repo Github: when we have made the local commits to the local repository, we can send this off to our central location and in this case, that will be Github.

Working with Git
-Command Line Interface(CLI): using this really gives developers the access to all commands available in Git.
-GUI (Github desktop, source tree, tower): They only support part of the available commands

Command Lines
-$ git
-$ git config: this command allows us to get and set configuration options, both globally, as well as for the current repository we're working with.
-$ git init: to create an empty repository
-$ git clone: this command is to clone a repository into a local directory on the machine and will also create a remote tracking branch and check out an initial branch.
-$ git add: using the add command, we can add a file or multiple files into the staging area. It basically makes Git include these files to the index, making them ready for a commit later on.
-$ git commit: this command will commit the changes to the local repository. A new commit is created and typically a commit message is sent along.
