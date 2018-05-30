 ## Learning Github Through Command
Download and initialize step by step

1. Signup and create a account on GitHub
2. Add your github email and username to git
	* git config -global user.email "eternal_britu@hotmail.com"
	* git config - global user.name "britu"
3. Add file/folders to git - tracking
4. Commands
	* Terminal - go to the location of the folder/project
	* git init (To see all folder)
	* defaults write com.apple.finder AppleShowAllFiles YES or No
	* git status (To see all file or folder in git)
	* git add (To add file)
	* git commit -m (message will be seen in ) 
5.  Create a remote repositore and all send to remote
	* git remote add origin https://github.com/britu/new.git
		* add. will add all files
	* then push to changes
	* git remote add origin then location of remote repo
	* git push -u origin master
	
 ## Enable git commands autocomplete and colors on Mac
	 For autocomplete
	1. Put git-completion.bash script to your home directory

 ## Branching and merging testing and validating
	
	* What are branches
	* How to create branch
	* How to checkout branch
	* How to merge branch to master
	* How to delete branch (local and remote)

## Branch create
	* git branch "branch name"
	* git checkout branch
	* git merge "branch name" : Merge new branch in master branch




 ### Commit, Push and Go

 1. Check virsion £ git --version
 2. $ git config --global user.name "Britu"
 3. $ git config --global user.email "eternal_britu@hotmail.com"
 4. $ git config --list 

 ### Need Help? 
 1. git help <verb>
 2. git <verb> --help

 ### Two common Scenario 
 1. git init (Initialize a Repository From Existing Code)
 2. ls -la (To see all the files)
 3. rm -rf (remove this(.git)) To not to track
 4. To bring it back -  git init

 ### Before we commit anything
 git status : To see status

 #### To not to seen project
 touch .gitignore (is a file to get ignore so no one can see it) .pys

 ### Add file
 1. git add -A
 2. git staus
 3. git commit -m "Init"
 4. git staus
 5. git log

 ### To Setup Remote
 #### To create the directory
  *  git remote add folder (githubRepo) and url
 #### Adding file and making changes online server
  * Push : git push 
 #### Download online server
  * Fetch : git fetch 
To Hide and Show folder


* echo "# new" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git remote add origin https://github.com/britu/new.git
* git push -u origin master
…or push an existing repository from the command line
* git remote add origin https://github.com/britu/new.git
* git push -u origin master

 