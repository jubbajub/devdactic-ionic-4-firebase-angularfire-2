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
