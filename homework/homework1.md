##	Homework \#1:

###	Part 1: Join GitHub

1. If you haven't already done so, create a GitHub account. It's free!

###	Part 2: Get Git Setup

1. Install Git on your home system / primary development system using **one** of the following links:
	* Download a compatible version of Git for your system: http://git-scm.com/downloads
	* Download a GitHub Desktop client for your system: [Mac](https://mac.github.com/) | [Windows](https://windows.github.com/)
2. Walk through the [Hello World Tutorial](https://guides.github.com/activities/hello-world/) at least once
3. Download the [GitHub Cheat Sheet](https://services.github.com/on-demand/resources/cheatsheets/) for easy reference!
4. Set up your global variables, using the following commands:
	* ```git config --global user.name "Your Full Name"```
	* ```git config --global user.email "Your email address"```

###	Part 3: Get the Git-Demo files

1. Decide on a location on your computer where you can download the Git-Demo repository
2. Navigate to that folder in Terminal (Mac) or Command Line (Windows):
	* type: ```cd path/to/your/file/```
	* for example: 
		* Mac/Linux: ```cd ~/Dropbox/Code/Git/```
		* Windows: ```cd Users\yourUserName\Code\Git\```
3. Copy the remote Git-Demo repository's code to your computer using ```git clone```:
	* ```git clone https://github.com/project-steward/Practice-Git```
	* _Note_: this will create a new folder in your directory called "Practice-Git" containing the cloned repository's files
4. Create a link to the remote GitHub repository you just created by using the command:
	* ```git remote add practice-origin https://github.com/project-steward/Practice-Git```


###	Part 4: Participate and practice Git!

1. After downloading the repo's files, go to the folder titled 'introductions' and create a new text file. Title the file with your name (ex: molly-watson.txt).
2. Fill the file with the following information (see introductions/molly-watson.txt for examples):
	* Name:
	* Tell us something about yourself:
	* Write a message for the group:
3. Next, open the file in the main Practice Git repository titled 'participants.txt', and add your name to the bottom of the list. 
4. In the Terminal / Command Line program, use the 'git status' command to check the state of your files. You should see that there is one new untracked file, and one new modified file.
	* ```git status```
5. Add / update these files by using the 'git add' command, like so:
	* ```git add introductions/your-name.txt```
	* ```git add participants.txt```
6. Run 'git status' again to make sure that your files will be included in the next commit you make.
7. Commit your changes! Use the command:
	* ```git commit -m "Adding my information to participants and introductions - YOUR INITIALS"```
8. Next, before you push to your repo, first do a 'pull' to make sure your repo is up-to-date.
	* ```git pull practice-origin master```
9. Lastly, push your changes to your repo! Use the following command: 
	* ```git push practice-origin master```
	* When you run this command, you will need to enter your GitHub username and password in order to proceed
10. Go to the [Project Steward Practice-Git Repository](https://github.com/project-steward/Practice-Git). Do your changes show up? 
	* If you have any problems, post them to the [#tech-help channel on Slack](https://project-steward.slack.com/messages/CBV8D17D4)