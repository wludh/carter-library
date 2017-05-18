# Git and GitHub Procedure

* Download Git Bash from [Git for Windows](https://git-for-windows.github.io/).
* Git Bash is a command line interface for using Git, a version control system. 
* Git is a way to track changes to files and folders on your computer. 
* GitHub is a website for sharing and publishing code. 
* It's possible to only use git on your computer without pushing to GitHub. It's also possible to only make edits in GitHub without using the command line. 
* For the project, the folder ```carter-library``` is the repository or "repo." All project files reside in this folder, with the exception of the inventory spreadsheet in Google Docs. 
* If you get stuck, 1) double check your typing and 2) google your error message. 

## Git workflow 
* Open Git Bash. 
* Navigate to the ```carter-library``` folder. 
* Type ```git pull origin master``` and press enter. Be in the habit of "pulling" to ensure you have the latest version of the files.
* Work on inventory + RDF gathering
* To save changes:
	* Type ```git add .```. Press enter. 
	* Type ```git commit -m "Enter message about your changes."```. Press enter. 
	* Type ```git push origin master```. Press enter. 
* Your files should now be synced in the [carter-library repository on GitHub](https://github.com/wludh/carter-library). 