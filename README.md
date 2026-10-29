# Student Feedback Management System

Students submit feedback; the admin sees it live (new-feedback toast, unread badge, review status).

## Files
- index.html      : the whole app (upload this to GitHub)
- firestore.rules : Firestore security rules (paste in Firebase console, already done)

## Deploy on GitHub Pages
1. Create a public repo (e.g. student-feedback) and upload index.html
2. Settings -> Pages -> Deploy from a branch -> main -> / (root) -> Save
3. Firebase -> Authentication -> Settings -> Authorized domains -> add <username>.github.io
4. Open https://<username>.github.io/student-feedback/

## Admin
Admin tab -> log in with the email/password created in Firebase Authentication -> Users.
The same email must be set in firestore.rules (replace REPLACE_WITH_ADMIN_EMAIL).
