# ionic-with-firebase-auth

https://javebratt.com/ionic-firebase-tutorial-list/

# Initialise

src/app/credentials.ts, example

// Initialize Firebase
const firebaseConfig = {
  apiKey: "",
  authDomain: "",
  databaseURL: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
};
export default firebaseConfig;

npm install

ionic build
ionic integrations enable capacitor
ionic cap add android
ionic cap sync
