https://devdactic.com/ionic-4-firebase-angularfire-2/

1. Creating the Firebase App

FIREBASE EINRICHTEN:
...
...
Firebase Hosting --> npm install -g firebase-tools

2. Starting our Ionic App & Firebase Integration

ionic start devdacticFire blank --type=angular
cd devdacticFire
 
npm install firebase @angular/fire
 
ionic g page pages/ideaList
ionic g page pages/ideaDetails
ionic g service services/idea

ADD FIREBASE CONFIG
UPDATE app.module.ts
UPDATE app/app-routing.module.ts

3. Creating a Firebase Data Service
UPDATE services/idea.service.ts

4. Displaying a Firestore Collection List
UPDATE pages/idea-list/idea-list.page.ts
UPDATE pages/idea-list/idea-list.page.html

5. Working with a Firestore Document
UPDATE pages/idea-details/idea-details.page.ts
UPDATE pages/idea-details/idea-details.page.html

-->THIS WORKS VERY WELL

npm install firebase @angular/fire
firebase init
firebase deploy

ionic build --prod
git log --oneline

-->THIS WORKS VERY WELL, weil npm install durchgeführt