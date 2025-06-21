## open Gitbash or vs code editor terminal
Navigate to the folder you want to turn into a repository(or create one)
mkdir my-project
cd my-project
pwd

## Initialize git
git init

# Create a README.md (optional but recommended)
echo "# My Project" > README.md

# - Stage and commit:
git add . 
git commit -m "Initial commit"
# - Make sure you're authenticated:
gh auth login
# Follow the interactive prompts to complete authentication.
gh auth status

# - Create a new repo 
gh repo create my-new-repo --public --source=. --remote=origin --push