# Create a GitHub repository, clone it locally using VScode

## 1 — How to create a repository on GitHub

- 1 login to GitHub
- 2 On home/dashboard page, either
  - 2.1 click the green buttom
    ![]()
  - 2.2 click the + icon
    ![]()
- 3 This redirects you to "Create a new repository” screen.
  ![]()
- 4 fill out basic information regarding the repository.
  - 4.1 Choose the owner
  - 4.2 Provide a repository name
  - 4.3 provide a short description in the description field.
  - 4.4 Specify whether the repository is Public or Private.
  - Public: anyone can see this repository on the internet.
  - Private: only YOU can choose who can see and commit to the repository.
- 5 Check “Initialize this repository with README” check box,
  to immediately clone the repository to your local computer.
- 6 “Add .gitignore: None” drop-down list
  A plain text file where each line contains a pattern to specify type of files/directories to ignore. This is placed in the rootfolder of the repository.
- 7. “Add a License: None” drop-down list
     to choose an open source license
- 8. Click on green button “Create repository”.
     ![]()
     You will be automatically redirected to the repository home page as soon as the creation is completed.

## 2 — Add dummy file to created remote repository

At this point, your repository only contains a README.md file.

- 1 Locate the “Upload files” button on the page and click on it:
- 2 Upload any files to the repository (drag and drop or “choose your files” link)

NOTE: Make sure that the files you are adding contain data. If not, GitHub will not allow you to upload it, as it will not be readable for Github.

- 3 In “Commit changes” add information note regarding your commit.
  To look back in the future and find out about specific commit.
- 4 Choose “Commit directly to the master branch” option.

NOTE: When working with a team, you either

- work in a feature branch, then make a pull request to the master
- or work with a different branching system.

- 5 Click “Commit changes” button to commit/upload file to remote repository.
  ![]()

## 3 — Connect to your remote repository in VScode

- 1 Obtain the URL of the remote repository.
- click on the green button “Clone or download”
- 2 Copy it to your clipboard.
- 3 Open the VSCode application
- 4 Switch to the source control tab
- 5 Choose the “Clone Repository” option.
  ![]()
- 6 Enter the repository URL. Hit Enter.
- 7 Pick a location to have your remote repositories be cloned into.
- 8 Click the “Select Repository Location” button.
  This will trigger VScode to communicate with the GitHub remote repository.
  ![]()
- 9 Authenticated with GitHub from VScode
- Provide your credentials and click on the Login button.
  ![]()
- 10 Click on the “Open” button: VScode opens the cloned repository (locally).In the Explorer pane the files are available now locally.
  ![]()
- 11 Open the specified folder the repo has been cloned into.
  The code from the remote repository has been successfully cloned/downloaded locally.
  ![]()
