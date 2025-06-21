## git push -u origin main error: 
- Check your current branch name
# Run:
git branch

# - If you're on a branch called master instead of main, then your push command should be:
git push -u origin master

# Make sure you’ve committed something
If this is a brand-new repo and you haven’t made a commit yet, Git has nothing to push. 
# Try:
git add .
git commit -m "Initial commit"

# Rename your branch if needed
If you want your branch to be called main (which is now the default on GitHub), you can rename it:

git branch -M main
git push -u origin main
