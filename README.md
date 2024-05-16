# Pre-Commit Hook use Gitleaks

This is a script that acts as a pre-commit hook for Git, using Gitleaks to check for secrets in the code before allowing a commit.

## Installation

1. Copy the provided script into a new file and save it with a `.sh` extension, for example `pre-commit.sh`.

2. Make the script executable: chmod +x pre-commit.sh
   
3. With the script installed as a pre-commit hook, it will run automatically each time you attempt a commit. If the script detects secrets in your code, it will reject the commit and display an error message stating that secrets were found. If no secrets are found, the commit is allowed.


