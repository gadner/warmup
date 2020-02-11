# Warmup Exercise
Welcome to STAC's CS485: Web Programming GitHub warmup exercise. In order to succesfully complete this exercise, you need to complete the following steps:
- This assumes you have already downloaded and installed Git in your computer. To follow the commands below: If you're using a Mac, you may use the <Terminal>, if you're using Windows, you may use <Git Bash>. Commands such as `pwd` will give you the location where you're. To 'get into a directory,' you need to `cd name_of_directory.`

1. Download/clone this GitHub repository (make sure you're in an 'easy to access' location. For example, I created a folder in my Desktop and called it 'projects':  
`git clone git@github.com:STAC-CS485/warmup.git`  
_You may need to add SSH keys to your GitHub account in order to be able to interact with the repository remotely. Please check [here](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account) for more information._

2. Create a new branch for your work:  
`git checkout -b name_of_your_branch` 

3. Make sure you're active in the new branch you created:  
` git branch`: A * will appear next to the branch that is currently active 

3a. Check the current git status:  
`git status` 
You should see a message like this towards the end: nothing to commit, working tree clean 
This means, there are no changes within the branch where you're. 

4. Create a new file (.txt format preferably) within the directory you're working on, write your name in it and save it.  

5. Check the current git status once again:  
`git status` 
Now, within the message received, you should see something that says: Untracked files and then lists your new file (red color).  

6. Add your file to git to start tracking it:  
`git add name_of_your_file.txt` 
By checking the status again, you will see that your file changes colors to green and now your file is listed as a 'new file'. This means that the file is now being tracked. Every time you make changes to your file, the status of the file changes. Once you're satisfied with the content of the file - in this case, we only want to have our names in it, then we're ready to commit it.  

7. Let's commit the file with a meaningful message for logging purposes:  
`git commit -m "Adding my new file file_name.txt to the warmup project"` 
If everything went well, a `git status` after the commit will show no other changes. Now it's time to push your changes up to the main repository.  

8. To push your changes up (for the first time):  
`git push --set-upstream origin name_of_your_branch` 

9. Once that's completed, come back to the repository and create a pull request for your changes to be added to the main project:  
- Go to the Pull requests tab and click on the *New pull request* button.
- Make sure the *base* branch is set as *master* and the *compare* branch is set as *name_of_your_branch*
- Add your message, then click on *Create pull request* 

10. Congratulation! You're all set. 

## Resources
- [GitHub Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
