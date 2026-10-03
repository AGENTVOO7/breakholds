Breakhold website (Privacy Policy + Delete Account page)

1) Replace placeholders in public/*.html:
   [Developer Name]  [contact email]  [Country]  [date]  [Year]

2) Upload with Firebase Hosting (free, uses your existing Firebase project):
   - Install Node.js (nodejs.org), then in a terminal:
       npm install -g firebase-tools
       firebase login
   - In this folder (where firebase.json is):
       firebase deploy --only hosting --project YOUR_FIREBASE_PROJECT_ID
     (Project ID: Firebase console > gear icon > Project settings > Project ID)

3) Your links:
   Privacy Policy URL : https://YOUR_FIREBASE_PROJECT_ID.web.app/privacy
   Delete account URL : https://YOUR_FIREBASE_PROJECT_ID.web.app/delete-account

   Open both in a browser (incognito) to check they load before pasting into Play Console.
