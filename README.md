 <script type="module">
        // Import the functions you need from the SDKs you need
        import { initializeApp } from "https://www.gstatic.com/firebasejs/9.6.6/firebase-app.js";
        import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.6.6/firebase-analytics.js";
        // TODO: Add SDKs for Firebase products that you want to use
        // https://firebase.google.com/docs/web/setup#available-libraries
      
        // Your web app's Firebase configuration
        // For Firebase JS SDK v7.20.0 and later, measurementId is optional
        const firebaseConfig = {
          apiKey: "AIzaSyBIIrSZCOQgFtvsCTSKELxaXeXK-AVCg3o",
          authDomain: "portfolio-responsive-final.firebaseapp.com",
          projectId: "portfolio-responsive-final",
          storageBucket: "portfolio-responsive-final.appspot.com",
          messagingSenderId: "774742012073",
          appId: "1:774742012073:web:3ecb77c438cec80f5ef9b8",
          measurementId: "G-FC9ER9MD2N"
        };
      
        // Initialize Firebase
        const app = initializeApp(firebaseConfig);
        const analytics = getAnalytics(app);
      </script>