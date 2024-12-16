# Git Commands Reference

## **Directory and File Management**
- **Create a directory:**
  ```bash
  mkdir git-for-devops
  ```
- **Change directory:**
  ```bash
  cd git-for-devops/
  ```
- **List files:**
  ```bash
  ls
  ls -l
  ls -a
  ```
- **Remove a file:**
  ```bash
  rm <filename>
  ```
- **Create and edit a file:**
  ```bash
  vim <filename>
  ```
- **Display file content:**
  ```bash
  cat <filename>
  ```
- **Create multiple files:**
  ```bash
  touch <filename1> <filename2>
  ```

## **Git Repository Management**
- **Initialize a repository:**
  ```bash
  git init
  ```
- **Check repository status:**
  ```bash
  git status
  ```

## **File Staging and Committing**
- **Stage a file:**
  ```bash
  git add <filename>
  ```
- **Unstage a file:**
  ```bash
  git rm --cached <filename>
  ```
- **Commit changes:**
  ```bash
  git commit -m "<commit message>"
  ```

## **Branching and Switching**
- **List branches:**
  ```bash
  git branch
  ```
- **Create and switch to a new branch:**
  ```bash
  git checkout -b <branch-name>
  ```
- **Switch to an existing branch:**
  ```bash
  git checkout <branch-name>
  ```
  or
  ```bash
  git switch <branch-name>
  ```

## **File Restoration**
- **Restore a deleted or unstaged file:**
  ```bash
  git restore <filename>
  ```

## **Logs and History**
- **View commit history:**
  ```bash
  git log
  ```
- **View condensed commit history:**
  ```bash
  git log --oneline
  ```

## **Example Workflow**
1. **Initialize repository:**
   ```bash
   git init
   ```
2. **Create and add files:**
   ```bash
   touch file1.txt
   git add file1.txt
   ```
3. **Commit changes:**
   ```bash
   git commit -m "Added file1.txt"
   ```
4. **Create a new branch and switch:**
   ```bash
   git checkout -b feature-branch
   ```
5. **View branch list:**
   ```bash
   git branch
   ```
