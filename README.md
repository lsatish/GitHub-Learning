#GIT HUB Documents

1. To create a new Project Directory: git init <Directory Name>
	This will create a new directory with the given name. Also a .git folder is created where GIT holds all its relavent files to maintain the source control
2. To create a repo for Exisitng Project: Navigate to the directory and enter the following command git init
	Creates a new Project with the directory name. Also we can see the .git folder is created
3. To add the newly changed/ modified files: git add <filename> to the staging area or the git index
	All the changes are added to the Staging but not commited
4. To commit the changes git commit -m “<comments>”
	-m is to add the comments, which will be helpful in refering back to check what exactly these new files or modified files do
5. By modifiing an exising commited file, we can add and commit at the same time git commit -am “<comments>”
