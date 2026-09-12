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


