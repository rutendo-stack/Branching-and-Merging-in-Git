# Branching-and-Merging-in-Git
1. To create and switch to the `installation-updates` branch:
   Command: `git checkout -b installation-updates`

2. To stage the `README.md` file for commit and commit with a message:
   Commands:
   `git add README.md`
   `git commit -m "Added Installation instructions to README.md"`

3. To switch back to the `main` branch:
   Command: `git checkout main`

4. To create and switch to the `usage-updates` branch:
   Command: `git checkout -b usage-updates`

5. To merge the `installation-updates` branch into the `main` branch:
   Command: `git merge installation-updates`

6. To simulate the merge conflict by attempting to merge the `usage-updates` branch:
   Command: `git merge usage-updates`

7. To mark the conflict as resolved by staging and committing the file with a new commit message:
   Commands:
   `git add README.md`
   `git commit -m "Resolved merge conflict between installation-updates and usage-updates"`
