
>## ***Basic GIT Commands***
<hr>

- `git init`: Initializes a new Git repository.

- `git clone <URL>`: Clones an existing repository into a new directory.

- `git add`: Adds changes to the staging area.

- `git commit`: Commits changes to the repository.

- `git status`: Shows the status of the working directory.

- `git log`: Shows the commit history of the repository.

- `git branch`: Lists all branches in the repository.

- `git checkout`: Switches to a different branch.

- `git merge`: Merges changes from one branch into another.

- `git push`: Uploads local changes to a remote repository.

- `git remote`: Manages connections to remote repositories.

- `git help`: Shows help information for Git commands.

<hr>

>### ***Steps for upload a git repository on github*** 

- Create a new repository on GitHub by clicking the "+" icon in the top right corner of the page and selecting "New repository".

- Give your repository a name, and optionally add a description and a license (MIT licence).

- Choose whether to make the repository public or private.

- Click the "Create repository" button.

- In your local Git repository, run the following commands:

   - Initialize a new Git repository by running `git init`.

   - Add your files to the Git repository by running `git add` . (this adds all files in the current directory and its subdirectories).

   - Commit your changes by running `git commit -m "Initial commit"`.

- Copy the URL of your GitHub repository by clicking the green "Code" button and selecting "HTTPS" or "SSH" depending on how you want to connect to the repository.

- Add the GitHub repository as a remote by running `git remote add origin <repository URL>`. Replace `<repository URL>` with the URL you copied in the previous step.

- Push your local Git repository to GitHub by running `git push -u origin master`.

