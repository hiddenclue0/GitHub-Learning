Git/GitHub
1.	Know about check if Git is properly installed and which git version is using:
•	Command:  Git –version				cmd
2.	Change the user name and e-mail address by Configure Git
•	Command: git config --global user.name 		“Name”
•	Command: git config --global user.email 		“Mail”
3.	Creating git folder
•	Command: mkdir 					“Folder Name”
4.	Open folder’s file in vs code or notepad
•	Command: code .
5.	Change Directory/Folder
•	Command: cd folder					“Folder Name”
•	Command: cd ..					 “Go back form folder”
6.	Start git in a Folder
•	Command: git init					“Initialize git”
7.	Create a file in repositoty
•	Command: touch file				“File Name”
8.	See all files in a repository
•	Command: ls
9.	Check the Git status
•	Command: git status
10.	Add activity to the Staging Environment
•	Command: git add ‘file’				“edited/created file”
11.	Add all files in the current directory to the Staging Environment
•	Command: git add –all
•	Command: git add -A
12.	Move from stage to commit Environment
•	Command: git commit -m "MESSAGE!"
13.	Skip staging Environment
•	Command: git commit -a -m "MESSAGE"
14.	Check the status to see the changes in a more compact way
•	Command: git status –short (-M, -A, -D, ??) ‘FileName’
15.	View the history of commits for a repository
•	Command: git log
16.	Need some help remembering the specific option for a command
•	Command: git commit -help
•	Command: git help –all
17.	See the branches in a repository
•	Command: git branch
18.	Create a new branch in a repository
•	Command: git branch ‘branch-name’
19.	Jump into another branch: 
•	Command: git checkout ‘branch-name’
20.	Creating a new branch and jump at one command
•	Command: git checkout -b ‘branch-name’
21.	Merge branch
•	Command: git merge ‘branch-name’ 	“Move preferred branch before”
22.	Delete branch
•	Command: git branch -d ‘branch-name’
23.	Add remote repository into local repository
•	Command: git remote add origin ‘URL’
24.	 push our master branch to the origin url
•	Command: git push --set-upstream origin master
25.	Colne a remote repo into local repo
•	Command: git clone “URL”
26.	local repository is up-to-date with the changes in the remote repository(pull)
•	Command: pull= “fetch and then merge”
•	Command: git pull origin
27.	fetch updates to see what has changed on GitHub
•	Command: git fetch origin
•	On this approach local repository is behind from the remote repo 
28.	Showing the differences between our local and remote repository
•	Command: git diff ‘Remote/Local’
29.	Merge remote repo and local repo
•	Command: ‘git merge Remote/Local
30.	push changes to remote origin
•	Command: git push origin
31.	Remote repositories new branch may not pull into local repo
•	Command: git branch -a  
32.	Push a new branch from local to remote repo
•	Command: git push origin ‘branch-name’
33.	The GitHub flow works like this:
a)	Create a new Branch
b)	Make changes and add Commits
c)	Open a Pull Request
d)	Review
e)	Deploy
f)	Merge
g)	Delete newly created branch
34.	Git can specify which parts of project should be ignored by creating file named
•	Command: touch .gitignore
35.	Edit .gitignore file
•	ignore ALL .log files
i.	Command: *.log
•	ignore ALL files in ANY directory named temp
i.	Command: temp/
36.	See All commits shortly
•	Command: git log –oneline
37.	modify the most recent commit
•	Command: git commit --amend -m "MESSAGE"
