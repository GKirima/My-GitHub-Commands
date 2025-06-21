## Logging in to GitHub using CLI
To log in to GitHub using the GitHub CLI (`gh`), use the following commands:

# $ git init
Initialize empty Git path repository in C:


# gh auth status
Check status of git - this will show you if you are logged in github. If not run the following command 

```sh
gh auth login
```

Follow the interactive prompts to complete authentication. You can choose to authenticate via a web browser or by pasting a token.

? Where do you use GitHub?  [Use arrows to move, type to filter]
*> GitHub.com*
  Other
? Where do you use GitHub?  *GitHub.com*
? What is your preferred protocol for Git operations on this host?  [Use arrows to move, type to filter]
*> HTTPS*
  SSH
? Authenticate Git with your GitHub credentials? *Yes*
? How would you like to authenticate GitHub CLI?  [Use arrows to move, type to filter]
*> Login with a web browser*
! First copy your one-time code: *1234-567*
Press *Enter* to open https://github.com/login/device in your browser... 
✓ Authentication complete.
- gh config set -h github.com git_protocol https
✓ Configured git protocol
✓ Logged in as *xyz*

## In case you don't have GitHub CLI use the following commands
# using winget: (Windows Package Manager)
winget install --id GitHub.cli
# using bash
scoop install gh

# Using Homebrew: For MacOS
brew install gh

# For Linux
# Using apt (Debian/Ubuntu):
sudo apt update
sudo apt install gh

# Once installed, you can authenticate with:
gh auth login