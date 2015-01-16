# LoginActivityTemplate


####This is a Login Activity teamplate for Android applications that use Parse as backend.

>It is intended to reduce the time taken to write a Login activity for Android apps.

>The template accounts for basic Login activity operations.

***
####Operations supported.
1. Signup with email and password.
2. Login with email and password.
3. Validation of email and password on Parse backend.
4. Eye candy alert boxes displaying the appropriate messages - Success or various failure cases.
5. If successfully logged in, then the next time the app is opened, it doesnt ask for login.

The template uses various 3rd part open source libraries. build.gradle scripts are also included.
***
####Contents
1. **LoginActivity.java** - The main class which handles the login functionality
2. **activity_login.xml** - The layout file which renders the UI
3. 2 **build.gradle** files - One for project, one for app

***

####How to use.
1. Copy the **LoginActivity.java** to your project.
2. Copy **activity_login.xml** to your res/layout folder.
3. Modify your **build.gradle** files with the content of the build.gradle scripts included.
4. Change the Parse **applicationId** and **client key** according to your own app.

Once these basic changes are made, you can customize the app using your own icons, fonts and backgrounds