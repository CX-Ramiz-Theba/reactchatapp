npm install firebase

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
const firebaseConfig = {
  apiKey: "AIzaSyCwriUPrW6uxmuuitj4AMEspCyfUw4SvCw",
  authDomain: "reactchatbotapp-27b3f.firebaseapp.com",
  projectId: "reactchatbotapp-27b3f",
  storageBucket: "reactchatbotapp-27b3f.appspot.com",
  messagingSenderId: "603952591887",
  appId: "1:603952591887:web:52007b49f9c70ea33d9f7a"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);



npm install -g firebase-tools

----------------------------------------------------


You can deploy now or later. To deploy now, open a terminal window, then navigate to or create a root directory for your web app.

Sign in to Google
firebase login
Initiate your project
Run this command from your app’s root directory:

firebase init
When you’re ready, deploy your web app
Put your static files (e.g., HTML, CSS, JS) in your app’s deploy directory (the default is “public”). Then, run this command from your app’s root directory:

firebase deploy
After deploying, view your app at reactchatbotapp-27b3f.web.app

Need help? Check out the Hosting docs

