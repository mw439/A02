-----------------------------------------------------------------------------------------------------------------------------------------------------------------
# What is GitHub? 
**GitHub**, Inc. is a platform and cloud-based service for software development and version control using Git, allowing developers to store and manage their code.
GitHub is one of the most popular resources for developers to share code and work on projects together. It’s free and a easy way to learn how to code various types of coding languages. 
Some of the core languages on GitHub, includes languages such as: C, C++, C#, Go, Java, JavaScript, PHP, Python, Ruby, Scala, and TypeScript

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Steps to Using GitHub:

# Task: Creating a Github Account
1. Search Up GitHub (or visit: https://github.com/) on your search engine or visit this direct sign up link here:
- https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home  
2. Make an Account (Create a Username and password)
  
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

COMMANDS are very useful when interacting with a remote repository. You can **clone** and **fetch** download remote code from a repository's remote URL to your local computer, **merge** can also be used to merge different people's work together with yours, and **pull** is a combination of **fetch** and **merge**.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Steps to use Git 



# Steps to use Webstorm 



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

# References
- https://docs.github.com/en/get-started/quickstart/github-glossary
   
- https://docs.github.com/en/get-started/quickstart/hello-world
  
- https://docs.github.com/en/get-started/learning-about-github/github-language-support
  
- https://blog.hubspot.com/website/what-is-github-used-for

- https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files

- https://docs.github.com/en/get-started/quickstart/create-a-repo

- https://docs.github.com/en/actions/using-workflows/about-workflows 


