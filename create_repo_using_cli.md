## open Gitbash or vs code editor terminal<br>
Navigate to the folder you want to turn into a repository(or create one)<br>
mkdir my-project<br>
cd my-project<br>
pwd<br>

## Initialize git<br>
git init<br>

# Create a README.md (optional but recommended)<br>
echo "# My Project" > README.md<br>

# - Stage and commit:<br>
git add . <br>
git commit -m "Initial commit"<br>
# - Make sure you're authenticated:<br>
gh auth login<br>
# Follow the interactive prompts to complete authentication.<br>
gh auth status<br>

# - Create a new repo <br>
gh repo create my-new-repo --public --source=. --remote=origin --push<br>
gh repo create my-github-commands --public --source=. --remote=origin --push<br>
git remote add origin https://github.com/Gkirima/My-GitHub-Commands.git<br>