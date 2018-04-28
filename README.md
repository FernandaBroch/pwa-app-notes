

Note App PWA
=================================================
This is a codelab, to learn how to make a progressive web app using Firebase and Polymer Web Components:
https://codelabs.developers.google.com/codelabs/polymer-firebase-pwa/index.html#2

App ready to test in:
https://pwapp-d86a4.firebaseapp.com/


Steps to run app with Cloud 9
=================================================

1. Firebase needs node version > v6.11.2 
nvm install 9

2. Firebase login 
firebase login --no-localhost

3. Install Firebase 
npm install -g firebase-tools

4. Use C9 port to start firebase server
firebase serve -p 8080 -o $IP

5.Platinum-sw was deprecated. (The readme was updated on Jul 19, 2017)
bower install -p platinum-sw

6.Browser Block third-party cookies 
Option should be off

7.Firebase Console Domain Authorization
Authentication > Sign-in method > Authorized domains
Add your appname-user.c9users.io 

==================================================
Firebase init
In question:
What do you want to use as your public directory? 
Change to ===> workspace



