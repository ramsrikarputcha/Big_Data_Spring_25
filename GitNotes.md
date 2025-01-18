# Git Notes

## Introduction to Git
Git is a distributed version control system that helps developers collaborate on projects. It tracks changes in source code during software development.
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Basic Commands

### Configuration
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Repository Setup
```sh
git init
git clone <repository_url>
```

### Staging and Committing
```sh
git status
git add <file>
git commit -m "Commit message"
```

### Branching
```sh
git branch
git branch <branch_name>
git checkout <branch_name>
git merge <branch_name>
```

### Remote Repositories
```sh
git remote add origin <repository_url>
git push origin <branch_name>
git pull origin <branch_name>
```

### Viewing History
```sh
git log
git log --oneline
```

## Best Practices
- Commit often with meaningful messages.
- Use branches for new features and bug fixes.
- Regularly pull changes from the remote repository to stay updated.

## Resources
- [Official Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
