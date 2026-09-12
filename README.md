Software Installation & SRS Document
1. SRS Document – A Practical Guide

What is SRS?
SRS (Software Requirements Specification) is a document that captures the complete software requirements.

Importance of SRS:
Acts as a blueprint for development.
Bridges the gap between client and developer.
Basis for validation and verification.


2. Structure of an SRS Document
1. Abstract
2. Functional Requirements (FR)
3. Non-Functional Requirements (NFR)
4. User Identification
5. Workflow of Each User
6. Use Cases

3. Abstract
Define the problem clearly.
Explain the purpose of the software and why the problem is important.
Explain what the software provides, including features and technology/method used.
Keep it concise, around 2–3 sentences.
Mention the outcome/result/use.

4. Example – Spotify-like App
“In Spotify many users seek a personalized music streaming experience across devices. However, current solutions may lack intuitive interfaces, offline support, or seamless playlist sharing. The proposed system offers a cloud-based music platform allowing users to stream, download, and organize music with personalized recommendations."

5. WhatsApp – Abstract
WhatsApp is a cross-platform instant messaging application that allows users to communicate via text, voice, images, documents, and video calls over the internet. It provides real-time, end-to-end encrypted communication, supports both individual and group chats, and includes features like status updates, media sharing, voice notes, and location sharing. The goal is to provide a secure, fast, and user-friendly communication tool accessible globally.


6. Functional Requirements (FR)

Functional Requirements are Mandatory Requirements.
They describe:
What the system should do.
The specific actions the system must perform.
Functions or services that the software provides to users.
Examples:

FR1: The user shall be able to sign up using an email ID.
FR2: The user shall be able to search for songs, albums, etc. by keyword.
FR3: The system shall allow users to create and modify playlists.

Sample Functional Requirements for WhatsApp

FR1: User registration and phone number verification via OTP.
FR2: View and sync contacts using the phone’s contact list.
FR3: One-to-one text messaging.
FR4: Sending/receiving media such as images, videos and documents.
FR5: User profile management such as photo, name and about.

7. Non-Functional Requirements (NFR)

Non-Functional Requirements are Optional Requirements.
They describe how well the system should perform.
They include system attributes such as:
Performance
Usability
Security
Scalability


Examples:

NFR1: The system should respond to user queries within 2 seconds.
NFR2: The application shall be available 24 × 7.
NFR3: The system should be able to handle thousands of users at the same time.

Sample NFRs for WhatsApp

NFR1: The system should support billions of users concurrently.
NFR2: Messages must be delivered with <1 second delay in ideal conditions.
NFR3: 99.99% uptime for the service.
NFR4: Data must be encrypted end-to-end.
NFR5: The interface must be responsive and work across Android, iOS, and Web.


8. Users of the System

Users of Spotify
Free User
Premium User
Admin

Users of WhatsApp

Registered User:
Any person who has signed up using a phone number.
Admin (Group Admin):
A user who creates a group or is given admin privileges.
Unregistered Contact:
A contact saved in a user’s phone but not yet on WhatsApp.
System (Backend Services):
Handles message routing, encryption, sync, and storage.


9. Workflow of Each User

Workflow defines the user role and actions.
Free User Workflow Example
Browse music (songs, albums, playlists)
Listen to music (limited access)
Search for music
Create an account
Play songs (with ads and limited skips)

Admin Workflow

Manage user accounts
Moderate content (songs, playlists, comments)
View user activity and statistics
Add and remove content (songs, albums, etc.)



10. Registered User Workflow – WhatsApp

A) Registration & Setup
1. Install the app.
2. Enter phone number.
3. Receive and enter OTP.
4. Set name and profile picture.

B) Messaging
1. View contacts who use WhatsApp.
2. Select a contact to chat.
3. Type and send message.
4. Message gets encrypted, sent to server, then to recipient.
5. View message delivery:



✓✓ blue




C) Calling

1. Tap on call icon.
2. Choose voice/video.
3. System connects via VoIP protocol.
4. End-to-end encrypted communication.


11. Group Admin Workflow – WhatsApp
1. Create a group and name it.
2. Add members from contact list.
3. Assign other admins (optional).
4. Control settings:

Allow all to send messages, or
Only admins can send messages.

5. Remove/add participants.


12. Use Case Diagram

The PPT contains a Use Case Diagram of the Spotify Music App.
It includes actors such as:
Free User
Admin
And use cases such as:
Browse/play songs, albums and playlists
Create an account
Add and remove content
View user activity and statistics
Manage accounts
Moderate content


13. Software Installation
STARUML
What is the use of STARUML?
StarUML is a software tool used to create diagrams that help in designing and understanding complex systems, especially in software development.
It allows you to visually map out how different parts of a system or application will work together, making it easier to plan, communicate, and build the system effectively.
It can be thought of as a drawing tool for software engineers to sketch out their ideas. 
How to install STARUML
1. Search for StarUML in Google.
2. Click on the official link.
3. Go to https://staruml.io/
4. Download StarUML for Windows/Mac.
5. Install the application.
6. Open StarUML after installation.
The PPT also shows the StarUML interface after installation. 

14. Git Bash

What is the use of Git Bash?
Git Bash is an application that lets you use Git commands on your computer.
Git:
A tool for tracking changes in files, mainly used for managing code in software projects.
Bash:
A command-line tool that allows you to type commands to perform various tasks on your computer.
Purpose:
Git Bash combines Git and Bash, so you can easily manage your code and use commands to work with files and projects. It helps in keeping track of changes and collaborating with others on coding projects. 
How to install Git Bash
1. Search for Git Bash in Google.
2. Click on the official link.
3. Go to https://git-scm.com/downloads
4. Download Git for Windows/Mac.
5. Install Git.
6. Open Git Bash after installation.
The PPT shows the Git Bash interface after installation. 


15. GitHub
What is the use of GitHub?
GitHub is a website where people can store and share their computer code.
It is like a big online folder where you can:
Keep your work
Make changes
Collaborate with others
Track changes
Keep projects organized
It provides a place where you and your team can work on a project together. 
How to create an account in GitHub?
1. Search for GitHub in Google.
2. Click on the official link.
3. Go to https://github.com/
4. Click on Sign Up.
5. Follow the signup steps.
6. Create your GitHub account.
7. After creation, the GitHub dashboard will be displayed.


LAB ACTION PLAN FOR WEEK 2

Objective: 
1.	Pushing multi-folder project into private repository (by student).
2.	Students must explore all listed git commands on the multi-folder project in local and remote repository.
3.	Students must explore all git commands on given scenario-based question.
4.	Students need to make note in observation book and also upload the executed exercise on scenario-based question.


Task 1: Pushing multi-folder project into private repository( Note: student take screenshots for upload).
1. Create a Private Repository on GitHub
•	Go to https://github.com
•	Click New repository
•	Give it a name
•	Check Private
•	Click Create repository
 2. Initialize Git in Your Local Project (if not already done)
     Open a terminal in the root of your multi-folder project:
  	cd /path/to/your/project
  	git init
3. Add the Remote Repository (in bash)
You’ll see a URL on GitHub after creating the repo. It will look as below , run  this command in git bash:
	git remote add origin https://github.com/yourusername/your-private-repo.git
4. Add and Commit Your Files(in bash)
	git add .
	git commit -m "Initial commit"
5. Push to the Private Repository 
If the repo is new and empty, push like this from git bash:
	git push -u origin master
If you're using the main branch (GitHub default):
	git push -u origin main
You may be prompted to log in (via username/password or token).

Task 2: Students must explore all listed git commands on the multi-folder project in local and remote repository.
1.	Git  Commands:
●	git version : The command git version is used to check the version of git. 
git --version
•	git config: Configures Git settings. Commonly used to set up user information
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
•	git config --list: Displays all the Git configurations for the current user.
2.	 Repository Management
•	git init: Initializes a new Git repository in the current directory
git init
•	git clone:  Creates a copy of an existing Git repository from a remote source (e.g., GitHub) to your local machine
	git clone https://github.com/username/repository.git
•	git remote –v : To see the remote repository that is connected to your local repository
 git remote –v

•	git remote add : To add a new remote repository to your local repository
  git remote add origin https://github.com/username/repository.git


•	Pushing Changes to Remote: To push your local commits to a remote repository:

         git push <remote_name> <branch_name>

		git push origin main

•	Pulling Updates from Remote: To pull the latest changes from the remote repository and merge them into your local branch
          git pull <remote_name> <branch_name>

          git pull origin main


•	git remote remove: To remove a remote repository from your local configuration:

            git remote remove <remote_name>

         git remote remove origin
•	Renaming a Remote:  to rename an existing remote: 

         git remote rename <old_name> <new_name>

	  git remote rename origin upstream

•	Fetching Updates from Remote: To fetch updates from the remote repository but not merge them into your local branch

	git fetch <remote_name>

•	Changing Remote URL : To change the URL of a remote (e.g., after changing the remote repository address):
	git remote set-url <remote_name> <new_url>

            git remote set-url origin https://github.com/username/new-repository.git

•	Viewing the Remote Repository’s Information: to see detailed information about a remote repository

            git remote show <remote_name>

            git remote show origin


3. Staging and Committing
•	git status: Shows the status of changes in your working directory and staging area. It tells you which files are untracked, modified, or ready to be committed.
git status
•	git add: Adds changes in the working directory to the staging area.
git add filename.txt   # Adds a specific file
git add .              # Adds all changes in the directory
•	git commit: Commits the staged changes to the repository with a descriptive message. The -m option allows you to include a commit message.
git commit -m "Commit message describing changes"
4. Branching and Merging
•	git branch: Lists all branches or creates a new branch
git branch                # Lists all branches or
git branch -a               # Lists all branches
git branch branch-name    # Creates a new branch
git branch -d <branch_name>    # Deletes a branch
                        Use -D to force-delete if it hasn't been merged.
•	Listing All Remote Branches :  To you want to list all branches on the remote repository
         git branch –r

•	git checkout: Switches to a different branch
git checkout branch-name  # Switches to an existing branch
git checkout -b new-branch # Creates and switches to a new branch
•	Pruning Deleted Remotes : If a branch was deleted on the remote but still shows up locally.
   git remote prune origin

When someone deletes a branch on the remote, your local Git doesn’t automatically remove the corresponding remote-tracking branch (like origin/old-feature).
git remote prune origin removes these outdated references.

•	Fetching a Specific Remote Branch: To fetch a specific branch from a remote.
     git fetch <remote_name> <branch_name>

	    git fetch origin feature-branch

•	Setting the Upstream Branch for Pushing : When pushing for the first time and want to set the remote branch you are pushing to:

	git push --set-upstream <remote_name> <branch_name>

       git push --set-upstream origin feature-branch

•	git merge: Merges the specified branch into the current branch. This command integrates the changes from the feature branch into the main branch.
git checkout main         # Switch to the main branch
git merge branch-name     # Merge branch-name into main
•	Rebasing a Local Branch onto a Remote Branch: If you want to rebase your local branch onto a remote branch (this can be useful to keep your history linear)
	git fetch <remote_name>
	git rebase <remote_name>/<branch_name>
Example:
	git fetch origin
	git rebase origin/main

5.	Undoing Changes

•	git reset : Removes the specified file from the staging area but leaves the working directory unchanged. git reset --hard can also reset the working directory and staging area to the last commit.
git reset <file>:
•	git revert: Creates a new commit that undoes the changes from a specified commit, leaving the history intact.
git revert <commit>:
6.	Viewing History

•	git log: Shows a history of commits in the repository, including commit hashes, messages, and timestamps. Use git log --oneline for a more concise view.
		git log:
•	git diff: Displays differences between various commits, the working directory, and the staging area. git diff without arguments shows changes not yet staged.
git diff:
•	git show:  Shows the details of a specific commit, including the changes made and the commit message.
git show <commit>
7.	To undo the changes made to file before staging it.

•	git restore filename
8.	To correct committed with the wrong message
•	git commit --amend -m "Corrected commit message"

9. Recovering deleted branches

•	git reflog
•	git checkout -b feature-ui <commit_hash>

10. To download the latest changes from the remote without merging
•	git fetch origin

11. To remove accidentally committed  sensitive file from Git history.

•	git filter-branch --force --index-filter \
•	"git rm --cached --ignore-unmatch secrets.txt" \
•	--prune-empty --tag-name-filter cat -- --all

12. To merge changes from another branch
First switch to branch where changes are to applied and then merge another-branch
•	git checkout previous-branch
•	git merge another-branch

13. To resolve a merge conflict manually
You tried to merge two branches and Git reported a conflict in x.js. Then for conflict resolution do:
1.	Open x.js and resolve/remove the conflict markers (<<<<<<<, =======, >>>>>>>)
2.	After resolving:
	git add app.js
	git commit  # If Git didn’t auto-create a merge commit

14. The .gitignore
The .gitignore file is used to tell Git which files or directories to ignore in your project. It's a useful way to avoid committing unnecessary files like log files, build outputs, and IDE configurations. 
a.	 Create a .gitignore File
In the root directory of your Git project, create a file called .gitignore 
touch .gitignore
b.	 Add Rules to .gitignore
Inside the .gitignore file, you add patterns for the files and directories you want Git to ignore. Each pattern should be written on a new line.
Here are some common examples:
•	Ignore all .log files:    *.log
•	Ignore a specific file:     secret_file.txt
•	Ignore all files in a temp/ directory:        temp/
•	Ignore all files except important_file.txt inside a folder:
folder/*
!folder/important_file.txt
•	Ignore files with a specific extension:    *.bak
15. To see who changed a particular line in a file
•	git blame script.py

16. Git stash
# You modified files A and B, but not committed them.
git stash             # saves changes and reverts to clean state
git switch another-branch
# do something else...
git switch main
git stash apply       # brings back your changes
17. To check branch is merge 
•	git branch –merged

If branch not merged then displays its name

18. To Delete multiple local branches at once

•	git branch –d branc1 branch2 branch3



WEEK 5 Docker CLI commands and Dockerfile
Objectives:
Students will able to:
•	Learn how to pull, run, stop, start, remove, and inspect containers and images.
•	Gain the ability to create, monitor, and troubleshoot running containers.
•	Configure and manage networks for container communication.
•	Create and manage persistent storage for containers.
•	Learn how to list, remove, and manage images efficiently.

Docker:
Docker is an open-source platform that automates the process of building, packaging, and running applications inside lightweight, portable containers, ensuring they run consistently across different environments.
Docker Images: 
A read-only template that contains the application code, runtime, libraries, and dependencies. It is like a blueprint for creating containers.
Docker Containers: 
A running instance of a Docker image.
Working with Docker CLI Commands:
Docker CLI Commands with redis
Step 1: Pull the redis Image
Command:
docker pull redis
Step 2: Run a Redis Container
Command:
docker run --name my-redis -d redis
What It Does:
• Creates and starts a container named my-redis from the redis image.
• The -d flag runs the container in the background.
Step 3: Check Running Containers
Command:
docker ps
What It Does:
• Lists all running containers.
Step 4: Access Redis
Command:
docker exec -it my-redis redis-cli
Opens the Redis command-line tool (redis-cli) inside the container.
Example Redis Commands:
127.0.0.1:6379> SET name "Alice"
OK
127.0.0.1:6379> GET name
"Alice"
127.0.0.1:6379>exit // to come out
Step 5: Stop the Redis Container
Command:
docker stop my-redis
What It Does:
• Stops the Redis container but doesn’t delete it.
Step 6: Restart the Redis Container
Command:
docker start my-redis
What It Does:
• Restarts the stopped container.
Step 7: Remove the Redis Container
Command:
docker rm my-redis  // Note before removing stop the container
What It Does:
• Deletes the container permanently.
Step 8: Remove the Redis Image
Command:
docker rmi redis
What It Does:
• Deletes the Redis image from your local system.

2.Working with Docker file
A Dockerfile is a text file with instructions to create a custom Docker image.
Step 1: Set Up Your Folder
1. Windows:
o Create a folder like C:\DockerProjects\Redis.
o Open Git Bash and navigate to the folder:
cd /c/DockerProjects/Redis
2. Mac/Linux:
o Create a folder:
mkdir ~/DockerProjects/Redis
cd ~/DockerProjects/Redis
Step 2: Write the Dockerfile
1. Inside the folder, create a file named Dockerfile (no extension).
2. Add the following content:
FROM redis:latest
CMD ["redis-server"]
Docker Commands (Step-by-step):
1. docker build -t redisnew  .
What it does:
• This creates (builds) a Docker image using the recipe (Dockerfile) in the current
folder (.).
• -t redisnew: Gives the image a name/tag ("redisnew"), so you can find it easily.
2. docker run --name myredisnew -d redisnew
What it does:
• Starts a new container (mini computer) from the redisnew image.
• --name myredisnew: Names the container "myredisnew" so it’s easy to identify.
• -d: Runs the container in the background.
3. docker ps
What it does:
• Shows a list of containers that are running right now.
4. docker stop myredisnew
What it does:
• Stops the container named "myredisnew" (like turning off a computer).
5. docker login
What it does:
• Logs you into your Docker Hub account, so you can upload images.
6. docker ps -a
What it does:
• Shows a list of all containers, including stopped ones.
7. docker commit 0e993d2009a1 budarajumadhurika/redis1 
// Note 0e993d2009a1 is container id of myredisnew
What it does:
• Takes a snapshot (saves changes) of the container with ID 0e993d2009a1 and creates a
new image called budarajumadhurika/redis1.
8. docker images
What it does:
• Lists all images saved on your system. // will show image of budarajumadhurika/redis1
9. docker push budarajumadhurika/redis1
What it does:
• Uploads the image budarajumadhurika/redis1 to Docker Hub, so others can download
it.
10. docker rm 0e993d2009a1  // container id of myredisnew
What it does:
• Deletes the container with ID 0e993d2009a1 of myredisnew.
11. docker rmi budarajumadhurika/redis1
What it does:
• Deletes the image budarajumadhurika/redis1 from your system.
12. docker ps -a
What it does:
Shows all containers again to confirm changes.
13. docker logout
What it does:
• Logs you out of Docker Hub.
14. docker pull budarajumadhurika/redis1
What it does:
• Downloads the image budarajumadhurika/redis1 from Docker Hub.
15. docker run --name myredis -d budarajumadhurika/redis1
What it does:
• Starts a new container using the image budarajumadhurika/redis1.
16. docker exec -it myredis redis-cli
What it does:
• Opens the Redis command-line interface (like a terminal) inside the running container
myredis.
17. SET name "Abcdef"
What it does:
• Saves a key-value pair in Redis (key = name, value = Abcdef).
18. GET name
What it does:
• Retrieves the value of the key name from Redis (it will return "Abcdef").
19. exit
What it does:
• Exits the Redis CLI.
20. docker ps -a
What it does:
• Shows all containers again to check their status.
21. docker stop myredis
What it does:
• Stops the container myredis.
22. docker rm 50a6e4a9c326
What it does:
• Deletes the container with ID 50a6e4a9c326.
23. docker images
What it does:
• Lists all images again to confirm which ones remain.
24. docker rmi budarajumadhurika/redis1
What it does:
• Deletes the image budarajumadhurika/redis1 again.
Step 3: Remove Login Credentials (Optional)
If you no longer need to be logged in, you can log out:
docker logout
What It Does:
• Logs you out from Docker Hub and removes your stored credentials.





