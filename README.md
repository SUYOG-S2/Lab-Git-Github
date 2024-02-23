# lab-git-and-github

I started by forking the repository named "lab-git-and-github" from the organization "Kalvium" to my own GitHub account. I renamed the forked repository to "Lab-Git-Github".

Then, I just copied the HTTPS link from the "Code" dropdown of my forked repository on GitHub.

Then, I opened Visual Studio Code and navigated to the main folder where i wanted to store it and work on it and I opened the integrated terminal in VS Code and ran the command git clone followed by the copied HTTPS link to clone the repository onto my local machine.

After cloning the repository, I changed directories into the folder by running cd main and the cd Lab-Git-Github to start working on it.

I created a new branch named "testing" using the command git branch Testing and switched to this branch using git checkout Testing.

In the VS Code editor, I made changes to the HTML file named "index.html" by replacing "John Doe" with "Suyog S Gouda". Additionally, I modified the CSS file "style.css" to change the font color from blue to red.

Once I made these changes, I saved them using command + s and returned to the terminal in VS Code.

I added all the changes to the staging area using the command git add . to include both the modified HTML and CSS files.

After staging the changes, I committed them with a descriptive message using git commit -m "Updated".

Next, I added a new remote repository reference to my local repository using the command git remote add remoterepo https://github.com/SUYOG-S2/Lab-Git-Github.git.

Finally, I pushed the changes to the remote repository on GitHub using git push --set-upstream origin Testing.

To verify that my changes were successfully pushed, I closed VS Code and opened my repository "Lab-Git-Github" on GitHub. I checked the HTML and CSS files to confirm that my changes were applied correctly.




