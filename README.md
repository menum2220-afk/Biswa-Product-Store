# BISWA MODS STORE

Files:
- index.html = customer store
- admin.html = admin panel
- assets/qr_code.png = PhonePe QR

Firebase:
1. Enable Realtime Database.
2. Enable Storage.
3. Enable Authentication -> Email/Password.
4. Enable Authentication -> Anonymous.
5. Create your admin email/password in Firebase Authentication.

Important:
- Replace the Firebase config if your project config changes.
- The current frontend uses Firebase client-side APIs.
- For production, configure strict Realtime Database and Storage Security Rules so only authenticated customers can create their own orders and only your admin account can approve/update orders.
