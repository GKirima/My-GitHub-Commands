## git push -u origin main error:<br> 
- Check your current branch name<br>
# Run:<br>
git branch<br>

# - If you're on a branch called master instead of main, then your push command should be:<br>
git push -u origin master<br>

# Make sure you’ve committed something<br>
If this is a brand-new repo and you haven’t made a commit yet, Git has nothing to push.<br> 
# Try:<br>
git add .<br>
git commit -m "Initial commit"<br>

# Rename your branch if needed<br>
If you want your branch to be called main (which is now the default on GitHub), you can rename it:<br>

git branch -M main<br>
git push -u origin main<br>
