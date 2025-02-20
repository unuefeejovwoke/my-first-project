# Git and GitHub Basics Assignment



## Initializing a Git Repository

### Commands Used

1. **Initialize the Repository**
   - Command:
     ```bash
     cd path/to/projects
     git init
     ```
   - Description: This command navigates to the `projects` directory and initializes a new Git repository by creating a `.git` directory.

### Outputs

- Added a screenshot or log showing the initialization of the Git repository. (Placeholder for screenshot/log)

## Adding and Committing Files

### Commands Used

2. **Add Files to Staging Area**
   - Command:
     ```bash
     git add .
     ```
   - Description: Adds all new or modified files to the staging area, preparing them for the next commit.

3. **Commit Files to Repository**
   - Command:
     ```bash
     git commit -m "Initial commit"
     ```
   - Description: Commits the staged files to the repository with a descriptive message.

### Outputs

- Added screenshots or logs showing the `git add` and `git commit` commands along with their outputs. (Placeholder for screenshots/logs)

## Pushing to GitHub

### Commands Used

4. **Link Local Repository to Remote**
   - Command:
     ```bash
     git remote add origin <repository-url>
     ```
   - Description: Links the local repository to a remote repository on GitHub, allowing local changes to be pushed.

5. **Push Changes to GitHub**
   - Command:
     ```bash
     git push -u origin main
     ```
   - Description: Pushes the local `main` branch to the remote repository `origin` and sets the upstream reference for future pushes.

### Outputs

- Added screenshots or logs showing the `git remote add` and `git push` commands and their effects. (Placeholder for screenshot/log)

## Cloning and Modifying Repositories

### Commands Used

6. **Clone Repository**
   - Command:
     ```bash
     git clone <repository-url> my-first-project-clone
     ```
   - Description: Clones the remote repository to a new folder on your machine for local development.

7. **Add and Commit New File**
   - Command:
     ```bash
     echo "List your programming goals here" > goals.txt
     git add goals.txt
     git commit -m "Added goals.txt with programming goals"
     git push
     ```
   - Description: Creates a new file `goals.txt`, adds programming goals, commits the new file to the repository, and pushes the update to GitHub.



