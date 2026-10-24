# Mobile App Notes - Besime Korkmaz

## What is React Native?
- React Native is a framework for building mobile applications using JavaScript.
- It allows developers to create applications for both iOS and Android.
- React Native uses reusable components to build user interfaces.

## What is Expo?
- Expo is a development platform for React Native applications.
- I used the command `npx expo start` to start the mobile application.
- I pressed `w` to open the application in my web browser.

## What I Learned
- The mobile application is called Book Exchange.
- The mobile application runs at http://localhost:8081.
- I used Chrome Developer Tools to test the mobile layout.
- I selected the iPhone 14 device profile.
- The mobile application communicates with the backend server on port 4000.

## Git Version Control
I used Git to track my work and upload my files to my own GitHub repository.

The Git commands I used were:

- `git status` - Check the status of my files.
- `git add` - Stage my changes.
- `git commit` - Save my changes in Git.
- `git push` - Upload my changes to GitHub.

## Conclusion
This activity helped me understand how React Native, Expo, and Git work together. I learned how to run a mobile application, test it in a browser, and manage my project using Git.

## Git Terminal Output Examples
### 1. Git Status

Command: `git status`

Terminal output:
On branch main
Your branch is up to date with 'myrepo/main'.

Changes not staged for commit:
        modified:   MobileStudent_Besime.md

no changes added to commit
### 2. Git Push

Command: `git push myrepo main`

Terminal output:

5637fc7..30d0497  main -> main

This confirms that my changes were successfully uploaded to my GitHub repository.
### 3. Git Add

Command: `git add MobileStudent_Besime.md`

Verification command: `git status`

Terminal output:

Changes to be committed:
        modified:   MobileStudent_Besime.md

This confirms that my file was staged and ready to be committed.
### 4. Git Commit
Command: git log -1

Terminal output:
commit 30d0497
Author: Besime Korkmaz
Date: Sat Oct 24 16:44:43 2026 -0400

    Add mobile Git workflow examples

This confirms that my changes were committed successfully and uploaded to my GitHub repository.

Command: `git commit -m "Add mobile Git workflow examples"`

This command saved my changes to the local Git repository.

I then used `git push myrepo main` to upload the commit to my GitHub repository.
