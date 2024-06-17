Repository Setup
I Logged in to my GitHub account.
Created a new repository on GitHub called "PLPBasicGitAssignment".
Initialized the repository with a README file.

Local Setup
I Created a new folder on my local machine called "PLPBasicGitAssignment".
Opened a terminal and navigated to the created folder.
Initialized a new Git repository in the local folder using the command:
git init

Connected the local repository to the GitHub repository using the command:
git remote add origin https://github.com/Angeth-Herjok/PLPBasicGitAssignment.git

Making Changes
I Created a new text file called hello.txt inside the local folder.
Added the text "Hello, Git!" to the hello.txt file.
Staged the changes using the command:
git add hello.txt

Committed the changes with a commit message:
git commit -m "Add hello.txt with a greeting"

Pushing to GitHub
Pushed the committed changes to the GitHub repository using the command:
git push -u origin main

Verification
I Visited the GitHub repository in a web browser and confirmed that the hello.txt file and commit message are visible.

