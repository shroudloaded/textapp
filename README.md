# Git Commands

## Setup and Configuration

### Install Git
**Windows:** Download from [git-scm.com](https://git-scm.com/downloads)

**Unix:**
```
sudo apt update
sudo apt install git
```

### Check Git Version
```
git --version
```

## Repository Management

### Initialize a Repository
```
mkdir [folder_name]
cd [folder_name]
git init
```

## Basic Operations

### Check Status
```
git status
```

### View Logs
```
git log
git log --oneline
```

### Show Commit Details
```
git show [commit_id]
```

### List Commits by Author
```
git log --author="[author_name]" --since="[start_date]" --until="[end_date]"
```

### Display Last Five Commits
```
git log -n 5
git log -n 5 --oneline
```

## Branch Management

### Create Branch
```
git branch [branch_name]
```

### Switch Branch
```
git checkout [branch_name]
```

### Merge Branch
```
git merge [branch_name]
```

## Stashing

### Stash Changes
```
git stash
git stash apply [stash@{index}]
git stash pop
```

## Cherry Picking

### Cherry Pick Commit
```
git cherry-pick [commit_hash]
```

## Reverting

### Revert Changes
```
git revert [commit_id]
```

## Remote Repositories

### Clone Repository
```
git clone [repository_url]
```

### Fetch and Rebase
```
git fetch origin
git rebase origin/[branch_name]
```

### Push Changes
```
git push origin [branch_name] --force
```

## Tags and Releases

### Create Tag
```
git tag [tag_name]
```

### View Tags
```
git tag
git show [tag_name]
```
