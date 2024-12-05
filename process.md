# Step-by-Step Process

This section will guide you through the process of creating a Git repository, making commits, and pushing changes to GitHub.

### Step 1: Create a Git Repository
1. Open the terminal or Git Bash.
2. Navigate to the directory where you want to create your project.
3. Run the following command to initialize a Git repository:
   ```bash
   git init
   ```
4. Create a new file in this directory (e.g., `README.md`) and add some content to it.

### Step 2: Commit Changes
1. To track your changes, add the new file to the staging area:
   ```bash
   git add README.md
   ```
2. Commit the changes to your local repository:
   ```bash
   git commit -m "Initial commit"
   ```

### Step 3: Push Changes to GitHub
1. Create a new repository on GitHub.
2. Copy the repository's HTTPS URL from GitHub.
3. Link your local repository to the remote GitHub repository:
   ```bash
   git remote add origin https://github.com/your-username/your-repository.git
   ```
4. Push your changes to GitHub:
   ```bash
   git push -u origin master
   ```

---

## Next: [Advanced Tips](advanced-tips.md)
