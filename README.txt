SOCIALCONNECT — GitHub Pages + Firebase starter

FILES
- index.html: the complete website
- firestore.rules: starter Firestore security rules

PUBLISH ON GITHUB
1. Open your GitHub repository.
2. Open index.html and replace its contents with the index.html in this folder.
3. Commit the change.
4. In Settings > Pages, choose Deploy from a branch, branch main, folder /(root), then Save.

FIREBASE SETUP
1. In Firebase Authentication, enable Google sign-in.
2. In Authentication > Settings > Authorized domains, add your exact GitHub Pages hostname, for example:
   YOUR-USERNAME.github.io
   Do not include https:// or a path.
3. In Firestore Database > Rules, paste firestore.rules and Publish.
4. Make sure the Firebase project is the one matching the configuration in index.html.

GOOGLE SEARCH CONSOLE
The requested google-site-verification meta tag is already in the <head> of index.html.
After GitHub Pages publishes, verify the exact website property in Google Search Console.

NOTES
- Firebase web config values identify the web app; they are not service-account credentials.
- Never put Firebase service-account private keys in website code.
- This is a starter community app. Review and strengthen rules and moderation/privacy controls before inviting the public.
