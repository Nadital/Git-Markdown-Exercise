#Basic Git Commands:

touch is used to create a new file

git init allows us to initialize the repository

vi or vim enters into the visual editor

	Opening VI, we are in the command mode. Use the VI Help sheet to determine what codes are needed to make changes
	Use cat to make sure the README.md file displays what was typed.

git add is used to add/update files to the tracked files in our repository
git add . will update all files

git status or git diff is used to identify what changes were made. git diff is for seeing the text. git status is used to see if changes need to be committed

git commit is used to take a snapshot of what was updated. It acts as a save. The full code used should be as follows: git commit -m "comments"

git push is used to push the data into the network repository on GitHub
Ideally, you would use git push origin master.

General order of operations is as follows:

1. touch (filename)
2. vi to edit
3. cat to check
4. git add . to stage all changes
5. git status to check for commits 
6. git commit -m with comments to commit them to the local repository
7. git push origin master to push them to the remote host


