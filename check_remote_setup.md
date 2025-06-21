# Check if a remote is set
# Run:
git remote -v

If nothing shows up, it means no remote is configured yet.
# Add the remote
# You’ll need to link your local repo to the GitHub (or other) remote. Use:
git remote add origin https://github.com/your-username/your-repo.git

# Replace the URL with your actual repository’s HTTPS or SSH link.

Push your code
# Now try:
git push -u origin master

# If you’re using the main branch instead of master, just swap that in:
git push -u origin main


## “Unable to add remote 'origin'”
git remote -v

If you see origin listed, that’s the culprit.
#  Remove the existing remote
git remote remove origin

# Re-run your gh repo create command (optional)
# Or, if the repo is already created and you just want to link it:
git remote add origin https://github.com/your-username/your-repo.git

# Then push:
git push -u origin main



