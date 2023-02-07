# online_examination_system

- [ ] mkdir <path> ==  make directory
- [ ] pwd == shows current directory path
- [ ] git config --global --list  == get all config information
- [ ] git add —a  == add all files in staging state
- [ ] git commit == commit the files
- [ ] git commit -m “type your msg”  == commit your file with msg
- [ ] git commit -a -m  “<message>” == commit code without staging the files
- [ ] git add <filename> ==  add a file to stage step
- [ ] rm -rf .git == remove git directory
- [ ] git clone <url> <folder_name>== clone the project from a url
- [ ] git diff == compare the working and staging directory
- [ ] git diff —staged == compare with staged file
- [ ] git rm <filename> == remove the file
- [ ] git mv <filename> <new filename> == rename the filename
- [ ] git rm —cached == to ignore any file from tracking
- [ ] git log == to check the commit status
- [ ] git log -p == to check the commit status with all changes
- [ ] git log -p <integer like 2>== to check the commit status with all changes (shows only 2 commits)
- [ ] git log -pretty=oneline == give all the commits list in one line
- [ ] git log -pretty=short == give all the commits list in short form
- [ ] git log -since=2.days == give all the commits list of last two days
- [ ] git restore —staged <filename> == unstage any file
- [ ] git checkout <filename> == change the file with the last commit
- [ ] git checkout -f == change all the file with the last commit
- [ ] git config —global alias.ci “commit”  == this makes the commit short as ci (now you can use git commit as git ci )
- [ ] git checkout -b develop == makes a “develop” named branch and makes you in that branch 
- [ ] git checkout master == switch to master branch 
- [ ] git branch == shows list of all branches
- [ ] git merge <branch name want to merge in master>  == merge the branch
- [ ] git branch -v == gives the last commit of all branches
- [ ] git branch —merged == shows list all merged branches
- [ ] git branch —no-merged == hows list all unmerged branches
- [ ] git branch -d <branch name> == delete branch( give error if branch is not merged )
- [ ] git push origin <branch name> == push the code in branch
- [ ] git push origin <branch name> :<new branch name> == push the code <branch name > by creating new branch <new branch name>

——————— GitHub
- [ ] Git remote origin <github folder path> == to add all files GitHub folder  (      Like : git remote add origin git@github.com:Codewithharry/gittutorialdemo.git   )
- [ ] git remote  ==  to check have any origin
- [ ] git remote  -v ==  to check have any origin with push and pull directions
- [ ] git push -u origin master == push the code in master (GitHub)
- [ ] git remote add origin git@github.com:DeveloperCodeinit/mine-Work.git 

—(for permission error)
- [ ] git remote (to check have connection or not if shows nothing then run next cmd)
- [ ] git remote add origin git@github.com:DeveloperCodeinit/mine-Work.git  (to add origin of GitHub user)
- [ ] ssh-keygen -t rsa -b 4096 -C "neha.codeinit@gmail.com" == to generate ssh key
- [ ] eval "$(ssh-agent -s)"  == to check the agent pid
- [ ] ssh-add ~/.ssh/id_rsa   == add ssh key to ids file
- [ ] tail ~/.ssh/id_rsa.pub. == to show the ssh key
- [ ] Copy the ssh key and add in the GitHub settings then push the code “git push -u origin master”.

