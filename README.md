# Hands-On Assignment: Basic Git And GitHub Workflow

# How to Create a Local Folder and Push it to Your GitHub Repository

In this guide, I will walk through the steps of creating a local folder on your computer and pushing it to your GitHub repository using Git Bash.

## Prerequisites

Before you begin, make sure you have the following:
- A GitHub account (create one if you don't have it already).
- A code editor of your choice (e.g., Visual Studio Code, Sublime Text).
- Git installed on your computer. You can download it from [here](https://git-scm.com/downloads).

## Steps

### 1. GitHub Repository Creation:

Log in to your GitHub account.

Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").

Initialize it with a README file.

### 2. Open Git Bash

Open Git Bash on your computer. You can find it in the Start menu (Windows) or Applications folder (macOS).

### 3. Navigate to Your Desired Location

Use the `cd` command to navigate to the location/directory where you want to create your local folder. For example, to navigate to your desktop:

```bash
cd Desktop
```

### 4. Local Folder Setup:

Create a new folder using the `mkdir` command at the desired location/directory on your local machine (e.g., "PLPBasicGitAssignment").
```bash
mkdir PLPBasicGitAssignment
```

### 5. Create a File inside the local folder:

Inside your local folder, using the `touch` command create a new text file
```bash
touch Hello.txt
```

Then using the `echo` command add a simple text message to the file
``` bash
echo "Hello, Git!" >> Hello.txt
```

### 6. Git Initialization:

Initialize a new Git repository in the local folder.
`git init`

### 7. Connecting to GitHub:

Link your local repository (local folder) to the GitHub repository you created in step 1.

```bash
git remote add origin <repository-url>
```
Replace `<repository-url>` with the actual URL of your GitHub repository.

### 8. Committing Changes:

Stage the changes.

```bash
git add Hello.txt
```
Commit the changes.

 ```bash
git commit -m "Add Hello.txt with a greeting"
```

### 9. Pushing to GitHub:

Push the committed changes to your GitHub repository.

```bash
git push -u origin main
```

### 10. Verify on GitHub:

Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.



    

