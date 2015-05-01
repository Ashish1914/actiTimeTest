# actiTimeTest
My first repository on GitHub for actiTime Tests
I would like to add few tests related to actiTime.

# SetUp Git and Github repository Instructions :
1. Go to "github.com" and sign up for free :) .
2. Login with your id and pwd.
3. Go to "git-scm.com/downloads" and download git shell. Install git on your machine.
4. Open git shell and then setup your git configuration using following cmd: 

$ git config --global user.name "YOUR NAME"
$ git config --global user.email "YOUR EMAIL ADDRESS"
$ git config --list  - Use to check ur configuration

5. Create a new repository(project folder) on GitHub and Initialize this repository with a README.
6. From your git shell navigate to the required directory and clone your remote directory to your machine.
$  git clone https://github.com/Ashish1914/actiTimeTest.git 


# Rename the file through Git:
There’s a specific Git way to do this, the git mv (or move) command. Follow git mv with the file’s current name, followed by its new name: $ git mv <oldName> <newName>
Running git status reveals that Git is aware of the name change, and ready for commit:
git status
 On branch master
 Changes to be committed:
   (use "git reset HEAD <file>..." to unstage)

	renamed:    TextFile.txt -> TextFileRename.txt

All that’s required now is to commit the change:
$ git commit -m "Test Rename"

Note that this will keep things simpler; if you use your operating system to rename a file, Git will think that the old file was deleted, and a new, untracked file was added. That makes for a messier, harder-to-follow commit history.

Now just push your changes to remote branch: 
$ git push origin master
