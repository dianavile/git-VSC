# Create a GitHub repository, clone it locally using VScode

## 1 — How to create a repository on GitHub

- 1 login to GitHub
- 2 On home/dashboard page, either
  2.1 click the green buttom
  ![]()
  2.2 click the + icon
  ![]()
- 3 This redirects you to "Create a new repository” screen.
  ![]()
- 4 fill out basic information regarding the repository.
  4.1 Choose the owner
  4.2 Provide a repository name
  4.3 provide a short description in the description field.
  4.4 Specify whether the repository is Public or Private.
  - Public: anyone can see this repository on the internet.
  - Private: only YOU can choose who can see and commit to the repository.
    5 Check “Initialize this repository with README” check box,
    to immediately clone the repository to your local computer.
    6 “Add .gitignore: None” drop-down list
    A plain text file where each line contains a pattern to specify type of files/directories to ignore. This is placed in the rootfolder of the repository.
  7. “Add a License: None” drop-down list
     to choose an open source license
  8. Click on green button “Create repository”.
     ![]()
     You will be automatically redirected to the repository home page as soon as the creation is completed.

## 2 — Add dummy file to created remote repository

At this point, your repository only contains a README.md file.

- 1 Locate the “Upload files” button on the page and click on it:
- Upload any files to the repository (drag and drop or “choose your files” link)

NOTE: Make sure that the files you are adding contain data. If not, GitHub will not allow you to upload it, as it will not be readable for Github.

- 3 In “Commit changes” add information note regarding your commit.
  To look back in the future and find out about specific commit.

- 4 Choose “Commit directly to the master branch” option.

NOTE: When working with a team, you either

- work in a feature branch, then make a pull request to the master
- or work with a different branching system.

-5 Click “Commit changes” button to commit/upload file to remote repository.
![]()

3 — Connect to your remote repository in VScode
Before we switch over to VScode, we first need to obtain the URL of the remote repository. To get the link you will need to click on the green button “Clone or download” and the link should appear as shown in the screen shot shown below:
Image for post

You can copy it to your clipboard now or you can come back to it when we are ready to connect to the repo within VScode.
Now let’s open the VScode application, when the application is completely launched switch to the source control tab (highlighted in step 1 in the screen shot shown below).
Once on the source control tab you will notice the prompt in step 2 in the screen shot below. What we will need to do is choose the “Clone Repository” option.
Image for post

Click on the “Clone Repository” option. You will notice that you are being prompted to enter a repository URL. In the prompt input box you will need to paste the URL for the repository that you have obtained in the previous steps.
Image for post

Once you paste the link and hit the “Enter” key, you will be prompted to select a location for the repository:
Image for post

Pick a location where you would want to have your remote repositories be cloned into and then click on the “Select Repository Location” button. This will trigger VScode to communicate with the GitHub remote repository. If you have not previously authenticated with GitHub from VScode you will be prompted to authenticate as shown in the screen shot below:
Image for post

Provide your credentials and click on the Login button. Once successfully authenticated you will notice the following notification in VScode:
Image for post

If you click on the “Open” button, VScode will open the newly cloned repository (locally).
In the Explorer pane you will notice that the “helloworld.js” as well as the “README.md” files are now available locally.
Image for post

If you open the folder where you specified the repo to be cloned into you will notice that the code from the remote repository has been successfully cloned/downloaded locally.
Image for post
