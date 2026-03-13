## Git Homework
This repo contains my solution for the Git homework.  

## Steps I Did

1. **Initialized the repository**
   - Created a Git repository using 'git init.
  
2. **Created a file and made messy commits**
   - Added `project.txt` and committed with unclear messages like 'update', 'stuff', 'final' and 'final final'.
   - Commands used: 'git add .', 'git commit -m "commit message"'

3. **Cleaned up commit history**
   - Used 'git rebase -i --root' to squash commits and write the commit "The project is up to date"

4. **Simulated a lost commit**
   - Added an experimental feature, then removed it with 'git reset --hard HEAD~1'
  
5. **Recovered the lost commit**
   -  Used 'git reflog' to find the lost commit.

6. **Created new branch for the recovered commit**
   -  Used 'git checkout -b feature-recovery ec4fe8' to create the branch and move the commit to 'feature-recovery'.

7. **Created Git alias for visual history**
   -  Used 'git config --global alias.visual "log --graph --oneline --all --decorate' to create it.

8. **Created Tagged version**
   -   git tag -a v1.0 -m "Version 1.0 – cleaned up version"

9. **Pushed to Github**
   -   git push -u origin master
    

  
