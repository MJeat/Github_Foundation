# How To Use Git
*Note: The documentation below is for beginner and intermediate GitHub and VSCode users* 

The documentation is about how to use git on VSCode to remotely publish file codes and the entire directories/folders into GitHub via git command lines. 
Another benefit of using Git Command Lines from VSCode is the quick and easy collaboration with others. Dragging and dropping folders and files through GitHub applications or webpages can be annoying, and can sometimes lead to errors or missing files or libraries.
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

## *Step 4 - Checking Remote*
In order to publish from VSCode to the GitHub app or webpage, your VSCode needs to be connected to your GitHub repository URL. 
To find this URL, I will take this repository as an example:
- On the top left corner, click Github_Foundation
- Look in the middle of the screen
- Try to find the read button that says ``` <> Code ```. Click on it
- In HTTPS, copy the link.
- The GitHub repository URL should look like this
```
https://github.com/MJeat/Github_Foundation.git
```





============================================================================================
# *Working With Git*
This is a walkthrough.
## *For Empty Repository on Github*
Please enter these code lines one at a time
```
git init
git add <Your files>
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MJeat/test.git
git push -u origin main
```


*Note: After ``` git remote add origin <Your git repo URL> ```, it is the best practice to initiate ``` git pull ``` first before cloning, publishing, or working on the repository, in general*





