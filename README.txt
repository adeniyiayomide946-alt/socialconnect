SOCIAL CONNECTS — WEBSITE STARTER
GitHub repository: socialconnect
Firebase project: socialconnect-81784

INCLUDED
- Google sign-in
- User profile (display name, username, bio)
- Text posts and live feed
- Likes and comments
- Delete your own posts
- Basic people search

INSTALL
1. Download and extract this ZIP.
2. Upload index.html to the root of your GitHub repository named socialconnect.
3. In Firebase Console > Firestore Database > Rules, paste firestore.rules and tap Publish.
4. In Firebase Console > Authentication > Settings > Authorized domains, add the GitHub Pages hostname only (example: YOUR-GITHUB-USERNAME.github.io).
5. Confirm Google is enabled under Authentication > Sign-in method.
6. In GitHub repository > Settings > Pages, choose Deploy from a branch, branch main, folder /(root), then Save.
7. Wait for GitHub Pages to publish. The usual URL format is https://YOUR-GITHUB-USERNAME.github.io/socialconnect/

IMPORTANT
The app is a starter, not a fully moderated public social network. Posts and profiles can be seen by signed-in users. Photo/video upload, following, private messages, notifications, blocking and moderation tools are not included yet. Add moderation and abuse controls before opening it widely.
The Firebase web API key is a client-side identifier, not a password. Never place service-account private keys in website code.
