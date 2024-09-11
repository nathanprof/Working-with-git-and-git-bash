##  Hagital Cloud Engineer program: git-lesson 101  
##  download git Bash  
https://git-scm.com/downloads  
##  Configure Git Bash  
- git config --global user-name "nathanprof"
- git config --config user.email "nathanXXX@gmail.com"
## Prepare Working Directory  
- mkdir website "I used this command "mkdir" to create a directory and named it website"
- cd website "I used this command "cd" to change to my directory website"
- git init "I used this command "git init" to initialize a new Git repository in my local directory in my Pc"
- touch index.html "I used this command "touch" to create an empty index.html file"
- vim index.html "I used this command "vim" to edit the html file"
- :wq "I first pressed the esc key then pressed the shift key then this commmand to save the file and exit"
##   Clone your Repository
-  git remote add origin (url) "This must be the https://url from my project Repo"
## Push to Github
- git add index.html "I used this command "git add" to stage changes for a commit"
- git commit -m "I used this command "git commit" to save the changes i made to my index.hml file then the flag "-m" to add a note"
- git push origin master "I used this command "git push" to upload or "push" my local repository's commits and changes to my Github account"
