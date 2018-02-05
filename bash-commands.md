# Bash Commands

**Replace [sqrackets] with your own words**

## Standard Console Commands
task | command
-----| -------
Make a new directory for your project | mkdir [new directory name]
List the contents of the directory you're inside | ls
Change directory to a directory that is inside the same one you are | cd [directory name]
Go back a directory | cd ..
Go back to the root directory | cd
Selects previous commands | up arrow key
Returns to a more recent command | down arrow key

## Git commands
task | command
-----| -------
Make the directory you're inside into a repository | git init
Add all files to the next commit that have been changed | git add .
Creates a commit of all the previously added files | git commit -m "[commit title]"
Upload all commits made since last push to github | git push
Establish the url of the github repo you would like to push to| git remote add [name (recommended: origin)] [github repository URL]
Open sublime and create a new file in the current directory (Example: README.me or .gitignore) | subl [file name]
Downloads the junit/mockito/hamcrest build.gradle file into your current directory | curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/junit-with-mockito-and-hamcrest/build.gradle --output build.gradle
Runs the gradle script, perform before importing to eclipse | gradle eclipse
