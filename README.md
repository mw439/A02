-----------------------------------------------------------------------------------------------------------------------------------------------------------------
# What is GitHub? 
**GitHub**, Inc. is a platform and cloud-based service for software development and version control using Git, allowing developers to store and manage their code.
GitHub is one of the most popular resources for developers to share code and work on projects together. It’s free and a easy way to learn how to code various types of coding languages. 
Some of the core languages on GitHub, includes languages such as: C, C++, C#, Go, Java, JavaScript, PHP, Python, Ruby, Scala, and TypeScript

------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Steps to Using GitHub:

# Task: Creating a Github Account
1. Search Up GitHub (or visit: https://github.com/) on your search engine or visit this direct sign up link here:
- https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home  
2. Make an Account (Create a Username and password)

# Task: Downloading Github Desktop
- It is also recommended to dowload the desktop version: https://desktop.github.com/ 
  
# Task: Creating a New Repository 
1. In the upper-right corner of any page(on Github), use the  drop-down menu, and select New Repository.
2. Type a short, memorable name for your repository. For example, this repository's name is named "A02".
3. You can also optionally add a description of your repository. (After naming your repository)
4. Click Create Repository
   
# Task: Creating a File 
1. In the **Repository** that you created previously, go to the upper right corner. You will see three main buttons. (Go to File, Add File, and <>Code(Green Button))
2. Click on Add Files. This will give you the drop down options on either Creating a new file or Uploading your own files.
3. Click on Create a new file
4. When you fully create a file, please remember to include a name in the file name field (ex: README.md). Type the name and extension for the file.
5. To create subdirectories, type the (/) directory separator. In the file contents text box, type content for the file. (This will determine the code and the type of files that would be able to be used for the file)

# Task/Fix: Making a Commit (Change/Revision)
1. After creating a file in the repository. To change the contents of the files (w/ information, code, comments, etc.. that you want to add/remove), you have to make a **Commit**. Commits are like snapshots of all the files in your project at a particular point in time.
2. When making "Commit Changes...", please notice some of the tools that are available to you:
- The Preview shows what the file would look like after the changes. After reviewing the preview you are able to decide whether you want to keep the commit.
- Review the changes you made to the file. If you select Show Diff, you will see the new content in green.
3. When your finally satisfied with the changes that are going to be made. Then you are ready to click "Commit Changes...'
4. If you want to make more changes click the edit file icon(pen icon) and repeat the previous steps on making a commit.

# Feature: Github WorkFlow
"Workflows are defined in the .github/workflows directory in a repository, and a repository can have multiple workflows, each of which can perform a different set of tasks. For example, you can have one workflow to build and test pull requests, another workflow to deploy your application every time a release is created, and still another workflow that adds a label every time someone opens a new issue." (Github)

# Features: Other commands/features/concepts
- **Branches** allows you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository. You always create a branch from an existing branch. Typically, you might create a new branch from the default branch of your repository. You can use a branch to isolate development work without affecting other branches in the repository. Each repository has one default branch, and can have multiple other branches. You can merge a branch into another branch using a pull request.
- **Merging(Merge)** allows you to combine branches into one. Sometimes **Merge conflicts** can happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge. Git can often resolve differences between branches and merge them automatically.
- **Fetch** allows you download files and changes from the **remote** to your local repository.
- Remember for **Remote**: A remote URL is Git's fancy way of saying "the place where your code is stored." That URL could be your repository on GitHub, or another user's fork, or even on a completely different server.
------------------------------------------------------------------------------------------------------------------------------------------------------------------
Basic Ideas: 
COMMANDS are very useful when interacting with a **remote** repository. You can **clone** and **fetch** download remote code from a repository's remote URL to your local computer, **merge** can also be used to merge different people's work together with yours, and **pull** is a combination of **fetch** and **merge**.

------------------------------------------------------------------------------------------------------------------------------------------------------------------
# What is Git?
**Git** is a distributed version control system(VCS) that tracks changes in any set of computer files, usually used for coordinating work among programmers who are collaboratively developing source code during software development. A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together.

Git allows developers see the entire timeline of their changes, decisions, and progression of any project in one place which is GitHub.

Please realize that: "GitHub hosts Git repositories and provides developers with tools to ship better code through command line features, issues (threaded discussions), pull requests, code review, or the use of a collection of free and for-purchase apps in the GitHub Marketplace. With collaboration layers like the GitHub flow, a community of 100 million developers, and an ecosystem with hundreds of integrations, GitHub changes the way software is built." 

The key difference is that: 
- Git is a version control system that lets you manage and keep track of your source code history.
- GitHub is a cloud-based hosting service that lets you manage Git repositories.

------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Steps to use Git 

# Task: Downloading Git
- To Download Git, go to this link:https://git-scm.com/downloads
- This link allows you to download a specific version of Git depending on the systems your using, they includes versions for
  - Linux/Unix
  - Windows
  - MacOS
- Understand that it is required to download Git to fully optimize the use with Github Desktop. (If you download GitHub Desktop it will also download the latest version of Git (only if you don't have it already))
- Dowloading Git will also allow you to utilize Git Bash
- For more details on installing Git please visit the website below:
- https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

# Feature/Task: Setting your Username for EVERY repository on your computer 
1. Open Git Bash
2. Set a Git username:
ex: git config --global user.name "Mona Lisa" 
3. Confirm that you have set the Git username correctly:
- ex: 
- $ git config --global user.name
- > Mona Lisa

# Feature/Task: Setting your Username for ONE repository on your computer 
1. Open Git Bash
2. Change the current working directory to the local repository where you want to configure the name that is associated with your Git commits.
3. Set a Git username:
ex: git config user.name "Mona Lisa"
4. Confirm that you have set the Git username correctly:
- ex:
- $ git config user.name
- > Mona Lisa

# Task: Setting your Commit Email Address
To set your email address please visit: 
https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address
(This is because there are various different instructions depending on the device/system that you are using)

# Feature: Using Git and GitHub
- You now have Git and GitHub all set up. You may now choose to create a repository where you can put your projects. Saving your code in a repository allows you to back up your code and share it around the world.
- Creating a repository for your project allows you to store code in GitHub. This provides a backup of your work that you can choose to share with other developers.
- Forking a repository will allow you to make changes to another repository without affecting the original.
- Each repository on GitHub is owned by a person or an organization. You can interact with the people, repositories, and organizations by connecting and following them on GitHub. For more information

# Feature: Basic Commands in Git
- git init: initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.
- git **clone**: creates a local copy of a project that already exists remotely. The clone includes all the project's files, history, and branches.
- git **commit**: saves the snapshot to the project history and completes the change-tracking process.
- git **status**: shows the status of changes as untracked, modified, or staged.
- git **branch**: shows the branches being worked on locally.
- git **merge**: merges lines of development together. This command is typically used to combine changes made on two distinct branches.
- git **pull**: updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.
- git **push**: updates the remote repository with any commits made locally to a branch.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

# What is Webstorm?
WebStorm is an integrated development environment for coding in JavaScript and its related technologies, including TypeScript, React, Vue, Angular, Node. js, HTML, and style sheets. WebStorm is a popular IDE used by web developers to make web applications. 

------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Steps to use Webstorm

# Task: Downloading Git
- To install WebStorm, go to the following URL: https://www.jetbrains.com/webstorm/download/#section=windows or visit https://www.jetbrains.com/help/webstorm/installation-guide.html#toolbox

# Task: Making an account on JetBrains 
- You can register and login by visiting this link: https://account.jetbrains.com/login

# Feature: How to use Webstorm/Linking it to Git/Github
All details regarding how to connect to Webstorm are linked here: 
- https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html#ws_getting_started_open_project 

------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Glossary 

- **Branch** :
A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
- **Clone** :
A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
- **Commit** :
A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
- **Fetch** :
When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.
- **GIT** :
Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
- **Github** :
GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
- **Merge** :
Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
- **Merge Conflict** :
A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
- **Push** :
To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
- **Pull** :
Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.
- **Remote** :
This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
- **Repository**: 
A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

# References

- https://docs.github.com/en/get-started/quickstart/github-glossary
   
- https://docs.github.com/en/get-started/quickstart/hello-world
  
- https://docs.github.com/en/get-started/learning-about-github/github-language-support
  
- https://blog.hubspot.com/website/what-is-github-used-for

- https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files

- https://docs.github.com/en/get-started/quickstart/create-a-repo

- https://docs.github.com/en/actions/using-workflows/about-workflows

- https://docs.github.com/en/get-started/using-git/about-git

- https://git-scm.com/downloads
  
- https://docs.github.com/en/get-started/quickstart/set-up-git

- https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git

- https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address
  
- https://www.jetbrains.com/webstorm/download/#section=windows or visit https://www.jetbrains.com/help/webstorm/installation-guide.html#toolbox

- https://account.jetbrains.com/login

- https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html#ws_getting_started_open_project 

------------------------------------------------------------------------------------------------------------------------------------------------------------------

