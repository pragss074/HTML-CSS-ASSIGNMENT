# Lab 1: Starting a Git Repository

## Student Information

| Field | Details |
|---|---|
| Name | Pragya |
| Student ID | BCS2025499 |
| Roll Number | 2510303373 |
| Email ID | pragya.rg2007@gmail.com |
| Subject | HTML and CSS Introduction Lab (BCS352) |
| University | Invertis University, Bareilly |

## Aim

To initialize a Git repository, configure local Git user information, create an HTML file, and save changes using Git commits.

## Tasks Performed

### Task 1: Initialize Git Repository
- Created a folder named `html-lab`.
- Initialized a Git repository using `git init`.
- Configured the local Git username and email.
- Verified the configured username and email.

### Task 2: Create First Commit
- Created an `index.html` file.
- Added an HTML heading to the file.
- Checked repository status using `git status`.
- Added the file to the staging area.
- Created the first commit with the message `Add home page`.

### Task 3: Create Second Commit
- Added an additional heading to `index.html`.
- Staged the modified file.
- Created the second commit with the message `Add next meeting heading`.
- Displayed the commit history using `git log --oneline`.

## Commands Used

```bash
mkdir html-lab
cd html-lab

git init

git config --local user.name "Pragya"
git config --local user.email "pragya.rg2007@gmail.com"

git config user.name
git config user.email

git status
git add index.html
git commit -m "Add home page"

git add index.html
git commit -m "Add next meeting heading"

git log --oneline
```

## Output

- Git repository initialized successfully.
- Local Git username and email configured successfully.
- HTML file created and committed successfully.
- Second commit created successfully.
- Commit history displayed successfully.

## Conclusion

Successfully initialized a Git repository, configured local Git user information, created an HTML file, and recorded changes using Git commits.
