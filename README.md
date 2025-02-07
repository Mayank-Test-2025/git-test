# Git Testing Commands f2:

This is a markdown file for testing Git commands and workflows.

## Setup

1. Initialize a new Git repository:
   ```sh
   git init
   ```
2. Configure user details:
   ```sh
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

## Basic Commands

- Check the status of your repository:
  ```sh
  git status
  ```
- Add files to staging:
  ```sh
  git add filename.md
  ```
- Commit changes:
  ```sh
  git commit -m "Initial commit"
  ```
- View commit history:
  ```sh
  git log --oneline --graph --decorate --all
  ```

## Branching

- Create a new branch:
  ```sh
  git branch new-feature
  ```
- Switch to the new branch:
  ```sh
  git checkout new-feature
  ```
- Merge branches:
  ```sh
  git checkout main
  git merge new-feature
  ```

## Remote Repositories

- Add a remote repository:
  ```sh
  git remote add origin https://github.com/user/repo.git
  ```
- Push changes:
  ```sh
  git push origin main
  ```
- Pull updates:
  ```sh
  git pull origin main
  ```

## Undo Changes

- Unstage a file:
  ```sh
  git reset HEAD filename.md
  ```
- Revert the last commit:
  ```sh
  git revert HEAD
  ```

## Additional Resources

- [Official Git Documentation](https://git-scm.com/doc)
