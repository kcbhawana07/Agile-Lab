# Lab 1

## Title: Introduction to Source Code Management using Git

### Objective:
To understand the fundamentals of source code management using Git.

- Initialize a Git repository
- Track changes using `git add`, `git commit`
- View version history
- Use branching and merging
- Push code to a remote repository (e.g., GitHub)

### Theory:
Source Code Management (SCM) is the practice of tracking and managing changes to code. It allows multiple developers to collaborate on code, track changes, roll back to previous versions, and maintain a history of a project.

Git is a distributed SCM tool widely used in software development. Key Git concepts:

- **Repository**: A Git project directory
- **Commit**: A snapshot of changes
- **Branch**: A parallel version of the repository, useful for working on features
- **Merge**: Integrating changes from one branch into another
- **Remote Repository**: A version of your project hosted on services like GitHub, GitLab, or Bitbucket

### Code:

#### Step 1: Initialize a Git repo
```bash
git init
```

#### Step 2: Add remote repository
```bash
git remote add origin https://github.com/kcbhawana07/Agile-Lab.git
```

#### Step 3: Check file status
```bash
git status
```

#### Step 4: Add files to staging
```bash
git add .
```

#### Step 5: Commit changes
```bash
git commit -m "commit message"
```

#### Step 6: View commit history
```bash
git log
```

#### Step 7: Create and switch to new branch
```bash
git checkout -b branchname
```

#### Step 8: Merge and switch to main branch
```bash
git checkout main
git merge branchname
```

#### Step 9: Push to remote repository
```bash
git push -u origin main
```

### Conclusion:
In this lab, we successfully learned how to manage source code using Git. We covered key commands like `init`, `add`, `commit`, `branch`, `checkout`, and `push`. Understanding Git is essential for collaborative software development, and this lab provided a practical foundation for future work in teams and version-controlled environments.
