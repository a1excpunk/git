# Git Basic Commands

## 1. Initialize a Repository

- Sets up a new Git repository. Use this to start tracking changes in a project.
  
```bash
git init
```

## 2. Clone a Repository

- Creates a local copy of the repository, including its entire history. Useful for contributing to remote projects.

```bash
git clone <repository-url>
```

## 3. Check Repository Status

- Shows the current state of the working directory and staging area. It tells you what files are modified or untracked.

```bash
git status
```

## 4. Stage Changes

- Prepares files for commit. You need to stage changes before committing them to the repository.
  
```bash
git add <file>  
```

- Stage all files at the same time

```bash
git add .
```

## 5. Commit Changes

- Records a snapshot of the changes made to the repository. It is important to include a meaningful commit message.

```bash
git commit -m "Your commit message"
```

## 6. View Commit History

- Displays a list of commits in the repository, showing who made the changes and when.

```bash
git log
```

## 7. Create a New Branch

- This allows you to work on new features or bug fixes without affecting the main codebase.

```bash
git branch <branch-name>
```

## 8. Switch Branches

- Switches to the branch you specify. This is useful when you need to work on a different feature or bug fix.

```bash
git switch <branch-name>
```

## 9. Merge Branches

- Merges the changes from one branch **into your current branch**. It’s typically used to bring feature branches into the main branch.

```bash
git merge <branch-name>
```

## 10. Delete a Branch

- Deletes the specified branch locally. It’s good practice to clean up old branches to keep the repository organized.

```bash
git branch -d <branch-name>
```

## 11. Push Changes

- Sends your committed changes to a remote repository, making them available to others working on the project.

```bash
git push <branch-name>
```

## 12. Pull Changes

- Downloads the latest changes from the remote repository and merges them into your local branch.

```bash
git pull <branch-name>
```

## 13. Check Remote Repositories

- Shows the remote repository URLs that your local repository is linked to, such as GitHub or GitLab.

```bash
git remote -v
```

## 14. Tags

- Tags are typically used to mark releases or milestones. They are like bookmarks in the repository’s history.

- Create a Tag

```bash
git tag <tag-name>
```

- See Tags

```bash
git tag
```

- Remove a Tag

```bash
git tag -d <tag-name>
```

## 15. Reset Changes

- This command allows you to remove changes you’ve made. Be cautious, as it can delete uncommitted changes.

```bash
git reset --hard <commit-hash>
```
