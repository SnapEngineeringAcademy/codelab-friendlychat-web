# Firebase Codelab: FriendlyChat

This code is forked from the [Firebase Web Codelab](https://codelabs.developers.google.com/codelabs/firebase-web/).

## How to Run

The completed code is in the `web` subfolder. In terminal, you can run by using `firebase deploy --except functions`

## Planned Changes for SEA
- Move the sign in to another page. Redirect from the sign-in page to the chat page. 
- Set up a basic HTML form on client-side (email, password)
- Send the form input to server → build a server
- Server communicates with Firebase Authentication
- Server redirects to the chat page 
- [already done, part of the starter code] Chat page communicates with Firestore to store messages 
- Netlify or some other platform to host the chat live
- If we have time... add the Bitmoji Kit to the chat platform


## How to make contributions?
Please read and follow the steps in the [CONTRIBUTING.md](CONTRIBUTING.md)


## License
See [LICENSE](LICENSE)
