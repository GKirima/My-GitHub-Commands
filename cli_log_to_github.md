## Logging in to GitHub using CLI<br>
To log in to GitHub using the GitHub CLI (`gh`), use the following commands:<br>

# $ git init<br>
Initialize empty Git path repository in C:<br>


# gh auth status<br>
Check status of git - this will show you if you are logged in github. If not run the following command<br> 

```sh
gh auth login
```

Follow the interactive prompts to complete authentication. You can choose to authenticate via a web browser or by pasting a token.<br>

? Where do you use GitHub?  [Use arrows to move, type to filter]<br>
*> GitHub.com*<br>
  Other<br>
? Where do you use GitHub?  *GitHub.com*<br>
? What is your preferred protocol for Git operations on this host?  [Use arrows to move, type to filter]<br>
*> HTTPS*<br>
  SSH<br>
? Authenticate Git with your GitHub credentials? *Yes*<br>
? How would you like to authenticate GitHub CLI?  [Use arrows to move, type to filter]<br>
*> Login with a web browser*<br>
! First copy your one-time code: *1234-567*<br>
Press *Enter* to open https://github.com/login/device in your browser... <br>
✓ Authentication complete.<br>
- gh config set -h github.com git_protocol https<br>
✓ Configured git protocol<br>
✓ Logged in as *xyz*<br>

## In case you don't have GitHub CLI use the following commands<br>
# using winget: (Windows Package Manager)<br>
winget install --id GitHub.cli<br>
# using bash<br>
scoop install gh<br>

# Using Homebrew: For MacOS<br>
brew install gh<br>

# For Linux<br>
# Using apt (Debian/Ubuntu):<br>
sudo apt update<br>
sudo apt install gh<br>

# Once installed, you can authenticate with:<br>
gh auth login<br>