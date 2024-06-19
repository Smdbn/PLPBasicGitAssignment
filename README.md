# PLPBasicGitAssignment
Week 3 Assignment 1 - Basic Git and Github workflow

Repository Setup
1. GitHub Repository Creation:

  - Log in to your GitHub account.

  - Create a new repository on GitHub (PLPBasicGitAssignment)

  - Initialize it with a README file.



Local Setup

2. Local Folder Setup:

  - Create a new folder on your local machine ("PLPBasicGitAssignment").

  - Open a terminal or command prompt and navigate to the created folder.



3. Git Initialization:

  - Initialize a new Git repository in your local folder.



4. Connecting to GitHub:

  - Link your local repository to the GitHub repository you created in Task 1.


git remote add origin <repository-url>


   Replace `<repository-url>` with the actual URL of your GitHub repository.



Making Changes

5. Create a File:

  - Inside your local folder, create a new text file (`hello.txt`).

  - Add a simple text message ("Hello, Git!").



6. Committing Changes:

  - Stage the changes.


   git add hello.txt


  - Commit the changes.


   git commit -m "Add hello.txt with a greeting"


Pushing to GitHub

7. Pushing to GitHub:

  - Push the committed changes to your GitHub repository.


   git push -u origin main

Verification

8. Verify on GitHub:

  - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.

