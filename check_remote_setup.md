# Check if a remote is set<br>
# Run:<br>
git remote -v<br>

If nothing shows up, it means no remote is configured yet.<br>
# Add the remote<br>
# You’ll need to link your local repo to the GitHub (or other) remote. Use:<br>
git remote add origin https://github.com/your-username/your-repo.git<br>

# Replace the URL with your actual repository’s HTTPS or SSH link.<br>

Push your code<br>
# Now try:<br>
git push -u origin master<br>

# If you’re using the main branch instead of master, just swap that in:<br>
git push -u origin main<br>


## “Unable to add remote 'origin'”<br>
git remote -v<br>

If you see origin listed, that’s the culprit.<br>
#  Remove the existing remote<br>
git remote remove origin<br>

# Re-run your gh repo create command (optional)<br>
# Or, if the repo is already created and you just want to link it:<br>
git remote add origin https://github.com/your-username/your-repo.git<br>

# Then push:<br>
git push -u origin main<br>



