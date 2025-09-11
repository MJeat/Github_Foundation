# How To Use Git
*Note: The documentation below is for beginner and intermediate GitHub and VSCode users* 

The documentation is about how to use git on VSCode to remotely publish file codes and the entire directories/folders into GitHub via git command lines. 
Another benefit of using Git Command Lines from VSCode is the quick and easy collaboration with people. Dragging and dropping folders and file through GitHub applications or web-page can be annoying, and can sometimes lead to errors or missing files or libraries.
This method is fast and time-saving for programmers. 

# First Time User
## *Step 1 - Creating GitHub Account and Repository*

- Create a GitHub account, one repository, and name it according to your preference
- For the repository, you may create or not create the README.md file. After that, proceed to create the repository 


## *Step 2 - Creating a Folder*

- On your computer, create a directory/folder and call it the same or a similar name to your repository

## *Step 3 - Enabling Git*
Enable Git:
  ```
  git init
  ```

If, however, no Git is found, you may need to install git:
  ```
  winget install --id Git.Git -e --source winget
  ```

After enabling git, you should see this output:
  ```
  Initialized empty Git repository in D:/...
  ```
Or
  ```
  Reinitialized existing Git repository in D:/...
  ```

## *Step 4 - Working With Git*
### *For Empty Repository on Github*



*Note: After ``` git remote add origin <Your git repo URL> ```, it is the best practice to initiate ``` git pull ``` first before cloning, publishing, or working on the repository, in general*





