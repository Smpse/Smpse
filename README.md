- 👋 Hi, I’m @Smpse
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Smpse/Smpse is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
FileInputStream serviceAccount =
new FileInputStream("path/to/serviceAccountKey.json");

FirebaseOptions options = new FirebaseOptions.Builder()
  .setCredentials(GoogleCredentials.fromStream(serviceAccount))
  .build();

FirebaseApp.initializeApp(options);
var admin = require("firebase-admin");

var serviceAccount = require("path/to/serviceAccountKey.json");

admin.initializeApp({
  credential: admin.credential.cert(serviceAccount)
});
<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.4.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.4.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyCfyj-h0TxeuFSm3B5GDtG2KrAFr-_gv_c",
    authDomain: "my-name-390215.firebaseapp.com",
    projectId: "my-name-390215",
    storageBucket: "my-name-390215.appspot.com",
    messagingSenderId: "860177406621",
    appId: "1:860177406621:web:3974e6e17653ca5ac71274",
    measurementId: "G-Q0C8XN5FNR"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>https://www.gstatic.com/firebasejs/10.4.0/firebase-app.jshttps://www.gstatic.com/firebasejs/10.4.0/firebase-analytics.js
my-name-390215.firebaseapp.com
