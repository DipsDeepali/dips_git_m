Download the git : https://git-scm.com/download/win
Install the git: 
	1. Just enable desktop icon.
	2. Enable the launch option.
	3. Disable the release info.
Open git bash.
Commands:
	$ pwd - to get the location of the folder.
	$ mkdir dips_git - create a directory.
	$ cd dips_git - change the directory.
	$ mkdir dips_git_m - create another directory to make this path as master branch with next cmd.
	$ git init - Initialize the local repository.
Work on your working directory and create the file (README.txt)
If we do 
	$ git add C:/Users/nikhi/README.txt
	error : C:/Users/nikhi/README.txt: 'C:/Users/nikhi/README.txt' is outside repository at 'C:/Users/nikhi/dips_git/dips_git_m'
Need to move the filr README.txt from working directory to git directory. Command:
	$  mv C:/Users/nikhi/README.txt C:/Users/nikhi/dips_git/dips_git_m/
For adding the file in staging area and commit in the locat repository(Master Branch)Command:
	$ git add
	$ git commit -m "commit the README file in the master branch of the local repository"
	error: Author identity unknown, unable to auto-detect email address
	$ git config user.email "nikhil.tandon2601@outlook.com"
	$ git commit -m "commit the README file in the master branch of the local repository"
Command:
	$ git diff - View the changes that were made in the file.
	


