

# Command Line Basics Assignment

This repository demonstrates fundamental command-line operations that involve creating directories and files, manipulating files, and basic text editing in Vim. The goal is to showcase command-line proficiency in managing file systems and documenting changes.

## Directory Structure Creation

### Commands Used

1. **Creating the Main and Sub-Directories**
   - Command:
     ```bash
     mkdir -p projects/week1 projects/week2
     ```
   - Description: This command creates a directory named `projects` and two subdirectories within it, `week1` and `week2`. The `-p` flag ensures that the entire directory path is created at once.

### Outputs

- Add a screenshot or log showing the created directory structure. (Placeholder for screenshot/log)

## File Operations

### Commands Used

2. **Creating an Empty File**
   - Command:
     ```bash
     cd projects/week1
     touch hello.txt
     ```
   - Description: Navigates to the `week1` directory and creates an empty file named `hello.txt`.

3. **Copying and Renaming the File**
   - Command:
     ```bash
     cp hello.txt ../week2/hello_copy.txt
     ```
   - Description: Copies `hello.txt` from the `week1` directory to the `week2` directory and renames it to `hello_copy.txt`.

4. **Deleting the Original File**
   - Command:
     ```bash
     rm hello.txt
     ```
   - Description: Deletes the `hello.txt` file from the `week1` directory.

### Outputs

- I added screenshots or logs showing the terminal output after each file operation. (Placeholder for screenshots/logs)

## Using Vim to Write a Text File

### Commands Used

5. **Writing in a Text File Using Vim**
   - Command:
     ```bash
     cd ../
     vim about_me.txt
     ```
   - Description: Navigates back to the root of `projects` and opens (or creates) `about_me.txt` in Vim. In Vim, `i` is used to switch to insert mode to type the text, and `:wq` to save and exit.

### Outputs

- I added a screenshot or log of using Vim to create and edit `about_me.txt`. (Placeholder for screenshot/log)



