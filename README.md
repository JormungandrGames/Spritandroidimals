# Spritandroidimals

### Developed by ```Insert Name Here```

###### Description
Spritandroidimals is a typical run and dodge android game.

###### Features
1. Level creator
	- 
2. High Scores
	- 

###### Workflow
1. Clone your fork to local computer:

	```
	git clone git@github.com:NAME/Spritandroidimals.git
	```
2. Add the master branch as the upstream

	```
	git remote add upstream git@github.com:BenKugler/Spritandroidimals.git
	```
3. Create a branch with this format

	```
	git branch feature_issue
	```
4. Add and commit

	```
	git add .
	git commit -m "Message"
	```
5. Push branch to origin

	```
	git push origin BRANCH_NAME
	```
6. Send pull request from your fork

	```
	Go to branch and click "Pull Request"
	```
7. Wait for a team member to merge and fix any conflicts if there are any
	* For fixing merge conflicts, make a file for the fix and pull the branch down
	
		```
		mkdir issue_#
		cd issue_#
		git clone git@github.com:NAME/Spritandroidimals.git
		cd Spritandroidimals

		git checkout -b punetid_issue_# master
		git pull https://github.com/NAME/Spritandroidimals.git puneid_issue_#

		fix conflicts

		git add .
		git commit -m "Message"

		git checkout master
		git merge --no-ff issue_#
		git push origin master
		```
8. After the pull request has been merged, on your local computer pull the changes down into you master and then push them to your fork

	```
	git checkout master
	git fetch upstream master
	git merge upstream/master
	```
9. You can now delete your branch

	```
	git branch -d issue_#
	```
