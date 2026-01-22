# Team Project – The GitHub Flow

## Overview
This project is used to practice team collaboration using Git and GitHub.  
Each team member works on their own branch and contributes a small change using a Pull Request.

---

## Project Workflow

### 1. Create the Central Repository
- One team member creates a central GitHub repository for the **Team Project**
- This person adds all other team members as **collaborators**

---

### 2. Clone the Repository
Each team member clones the repository to their local machine:

```bash
git clone <repository-url>
```

### 3. Create a Feature Branch

Each team member creates their own branch using their name:

```bash
git switch -c feature/your-name
```

Example:

```bash
git switch -c feature/alex
```

### 4. Add a Personal File

Each team member creates a file named:

***your-name.txt***


The file should contain a short bio about the team member

### 5. Commit Changes

Each team member stages and commits their work:

```bash
git add .
git commit -m "Feat: Add bio for your-name"
```

### 6. Push the Branch to GitHub

Each team member pushes their branch to the remote repository:

```bash
git push origin feature/your-name
```

### 7. Open a Pull Request

On GitHub, each team member opens a Pull Request

The Pull Request merges:

feature/your-name → main

### 8. Review and Merge

The repository owner reviews each Pull Request

Approved Pull Requests are merged into the main branch
