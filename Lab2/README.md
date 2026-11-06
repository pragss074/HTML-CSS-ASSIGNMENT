<!--
Name: Pragya
ID: BCS2025499
Roll No.: 2510303373
Email ID: pragya.rg2007@gmail.com
Subject: HTML and CSS (BCS352)
-->

# Lab 2: Pushing and Cloning a Repository

## 1. Experiment Title
Pushing and Cloning a Repository

## 2. Aim
To create a bare remote repository, connect it to a local repository, push commits and clone the remote repository.

## 3. Software / Tools Required
- HTML5 and CSS3 (where applicable)
- Visual Studio Code or any text editor
- Git and GitHub (for Labs 1 and 2)
- Web browser (for HTML/CSS practicals)
- Command Prompt / Terminal (for Git practicals)

## 4. Theory
A remote repository stores a copy of project history that can be shared or used as a backup. A bare repository contains Git data without a working directory. `git remote add` connects a remote, `git push` uploads commits, and `git clone` creates a local copy.

## 5. Algorithm / Procedure
1. Create a bare repository using `git init --bare`.
2. Connect it to the local repository with `git remote add origin`.
3. Verify the remote using `git remote -v`.
4. Push the local branch using `git push origin main`.
5. Move to the parent directory and clone the remote repository.
6. Open the cloned folder and inspect its history using `git log --oneline`.

## 6. Program / Queries / Commands
`git init --bare ../html-remote`  
`git remote add origin ../html-remote`  
`git remote -v`  
`git push origin main`  
`cd ..`  
`git clone html-remote html-copy`  
`cd html-copy`  
`git log --oneline`

## 7. Input
An existing local Git repository with at least one commit and a destination folder for the remote and cloned copy.

## 8. Output
The push completes successfully and the cloned repository contains the committed files and history. Refer to the terminal screenshots in the `images` folder.

## 9. Result
Successfully created a bare remote repository, pushed commits and cloned the repository.

## 10. Viva-Voce Questions
1. What is a remote repository?
2. What is a bare repository?
3. What does `git push` do?
4. What is the purpose of `git clone`?
