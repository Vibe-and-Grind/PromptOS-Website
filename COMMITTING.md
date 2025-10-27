# How to Commit Code

Follow these steps to save your changes to the repository.

1. **Check the current status**
   ```bash
   git status
   ```
   Review the output to confirm which files are staged or unstaged.

2. **Stage the files you want to include in the commit**
   ```bash
   git add <file1> <file2>
   ```
   Use `git add .` if you want to stage all modified files.

3. **Verify the staged set**
   ```bash
   git status
   ```
   Ensure the files you expect to commit are listed under "Changes to be committed."

4. **Commit with a concise message**
   ```bash
   git commit -m "Describe your change"
   ```
   Keep the message short and descriptive (e.g., `git commit -m "Fix mobile nav toggle"`).

5. **Push the commit to the remote branch**
   ```bash
   git push
   ```
   This publishes your commit so others can access it.

6. **(Optional) Create a pull request**
   If you're working on a collaborative project, open a PR with a summary of the changes and any testing performed.

For more details, consult the official [Git documentation](https://git-scm.com/doc).
