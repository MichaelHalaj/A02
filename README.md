# A02
## Tutorial: Using Git, WebStorm, and Github
### Prerequisites:
- Git installed on your local machine, which you can download from [here](https://git-scm.com/).
- WebStorm installed and setup, which you can download from [here](https://www.jetbrains.com/webstorm/).
- A GitHub account, which you can up for one here [here](https://github.com/).

### Step 1: Set Up Git and GitHub
1. Install Git on your local machine by following the installation instructions provided on the Git website.
2. Sign in to your GitHub account or create a new one if you haven't already.
3. Create a new repository on GitHub by clicking on the "+" icon in the upper-right corner and selecting "New repository". Give it a name, optionally add a description, and choose other settings as needed. Then, click "Create repository".

### Step 2: Configure WebStorm
1. Open WebStorm and navigate to `File` > `Settings`.
2. In the settings window, go to `Version Control` > `Git`. Make sure the path to the Git executable is correctly set. If Git is installed in the default location, WebStorm should detect it automatically.
3. Next, go to `Version Control` > `GitHub` and log in with your GitHub credentials to link your GitHub account with WebStorm.

### Step 3: Clone Your Repository
1. In WebStorm, select `VCS` > `Get from Version Control` > `Git`.
2. Copy the URL of your GitHub repository and paste it into the "URL" field in the dialog box.
Choose the directory where you want to clone the repository on your local machine and click "Clone".
3. WebStorm will clone the repository and set up the project for you.

### Step 4: Work with Branches and Commits
1. Open the project in WebStorm and start making changes to the code.
2. Before making any significant changes, create a new branch by clicking on the branch name in the bottom-right corner of the IDE and selecting "New Branch". Give your branch a descriptive name related to the feature or fix you're working on.
3. Make your changes to the code and save your files. Once you're satisfied with your changes, it's time to commit them.
4. Open the "Version Control" tool window in WebStorm by selecting `View` > `Tool Windows` > `Version Control`.
5. You'll see a list of changed files. Select the files you want to commit, enter a commit message describing your changes, and click "Commit".

### Step 5: Push Changes to GitHub
1. After committing your changes, you need to push them to your GitHub repository.
2. In WebStorm, go to `VCS` > `Git` > `Push`.
3. Make sure the correct branch is selected, then click "Push". This will upload your commits to the remote repository on GitHub.

### Step 6: Collaborate and Merge Changes
1. If you're collaborating with others, they can clone the repository from GitHub using the same URL.
2. When someone else makes changes to the repository and pushes them to GitHub, you can pull those changes into your local repository by selecting `VCS` > `Git` > `Pull` in WebStorm.
3. If there are any merge conflicts, WebStorm will help you resolve them by highlighting the conflicting lines and allowing you to choose which changes to keep.
4. Once conflicts are resolved, commit the changes and push them to GitHub as described in Steps 4 and 5.
## Glossary
- ***Branch***: A parallel version of a repository's code or history that diverges from the main line of development, allowing developers to work on features or fixes independently.

- ***Clone***: To create a copy of a repository, including all of its files, branches, and commit history, typically used to start working on a project locally.

- ***Commit***: A snapshot of changes made to files in a repository at a specific point in time. Commits are used to record and save changes with a message describing the modifications.

- ***Fetch***: A Git command used to retrieve changes from a remote repository without merging them into the local branch, allowing users to review changes before incorporating them.

- ***GIT***: A distributed version control system used for tracking changes in source code during software development. It enables collaboration among multiple developers working on the same project.

- ***GitHub***: A web-based hosting service for Git repositories, providing tools for collaboration, code review, and project management. It allows users to share and contribute to open-source projects.

- ***Merge***: The process of combining changes from one branch (source) into another branch (target). It's typically used to integrate features or bug fixes into the main development branch.

- ***Merge Conflict***: A situation that occurs when Git is unable to automatically merge changes from different branches due to conflicting modifications in the same part of a file. Developers must manually resolve these conflicts.

- ***Push***: A Git command used to upload local repository changes to a remote repository, making them accessible to other developers. It updates the remote branch with the latest commits.

- ***Pull***: A Git command used to fetch and merge changes from a remote repository into the current local branch, keeping it up-to-date with the latest modifications made by other developers.
  
- ***Remote***: A version of a repository hosted on a server, typically accessed via a URL. It allows multiple developers to collaborate on the same project by sharing code and changes.

- **Repository**: A central location where files, code, and project history are stored in a version control system like Git. It contains all the data and metadata necessary to manage and track changes to the project over time.

## References:
Git: Webstorm. WebStorm Help. (2023). https://www.jetbrains.com/help/webstorm/using-git-integration.html 

Hello world. GitHub Docs. (2024). https://docs.github.com/en/get-started/start-your-journey/hello-world 

Hendela, A. H. (2024). Introduction to Github and Webstorm. Lecture. 


