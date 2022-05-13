# PT-Finder

PT Finder is for anyone who is looking to start or improve their fitness journey with the help of a personal trainer.
A lot of people looking to begin their fitness journey struggle to connect with Personal Trainers outside of the commercial gym setting.
PT Finder is designed to break down this barrier by connecting fitness enthusiasts with Personal Trainers
while also allowing Personal Trainers to market themselves and attract more clients.
The app allows users to search for Personal Trainers via location and record statistics of their fitness journey.

# Launching the PT-Finder app

Instructions on launching this project are given in the section "To run this project" below.

The app is responsive but is primarily designed to be viewed on a screen with mobile phone dimensions.

This project uses a Firebase Firestore database and Firebase authentication.
It requires a firebase.config.js file creating within the src folder.

# Create a firebase.config.js

A file "firebase.config.js" needs to be created in the ./src folder
which contains the relevant security information provided in the Firestore settings.
The file needs to contain the following lines most of which can be copied and pasted from the Firestore settings

```
const firebaseConfig = {
apiKey: "XXX",
authDomain: "XXX",
projectId: "XXX",
storageBucket: "XXX",
messagingSenderId: "XXX",
appId: "XXX",
};


// Initialize Firebase
const app = initializeApp(firebaseConfig);

export { firebaseConfig };
```

# To run this project:

```
cd react-native-app
npm install
npm install react-native
npm start (expo start)
```

# Troubleshooting:

```
node -v (needs to be version 16)
nvm (check if installed)
nvm use node 16 (if doesn't work : nvm install 16)
nvm use node 16
```
