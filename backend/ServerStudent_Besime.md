# Server Setup Notes - Besime Korkmaz

## Starting the Backend Server

I cloned the IFT458 Middleware 2026 repository from GitHub and opened the project in Visual Studio Code.

I opened the backend folder and used the following command to start the server:

node server.js

The backend server runs at http://localhost:4000.

## Testing the Application

I opened the application in my web browser and confirmed that the backend was running.

The terminal displayed "DB connection successful!", confirming that the database connection was working.

## What I Learned

I learned how to clone a GitHub repository, start a Node.js backend server, and test the application in a browser.

I also learned how to use Git commands to track changes and push my work to my own GitHub repository.
## Git Workflow
I used Git to track my changes and upload my work to GitHub.

1. git status
   I checked which files were new or modified.

2. git add ServerStudent_Besime.md
   I added my server notes to the staging area.

3. git commit -m "Add Besime server setup notes"
   Git saved my changes in commit 94b961d.

4. git push myrepo main
   I successfully uploaded my changes to my GitHub repository.
### Terminal Output Example

Command: git show --stat 94b961d

commit 94b961d
Author: Besime Korkmaz
Date: Sat Oct 24 14:30:30 2026 -0400

Add Besime server setup notes

backend/ServerStudent_Besime.md | 23 +++++++++++++++++++++++
1 file changed, 23 insertions(+)
