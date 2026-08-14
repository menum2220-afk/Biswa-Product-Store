STORE SETUP
Files: index.html, qr_code.png, video.mp4, ambient.mp3
Upload all four to the root of the Store GitHub repository.

The video and sound are original generated assets. Browser autoplay sound is restricted; the store starts sound after the user's first interaction.

Important: saved balance purchases create a balance checkout request. On a free/static Firebase setup there is no trusted server to deduct wallet funds automatically. Admin approves the balance order and the admin panel performs the balance deduction atomically. This avoids letting a user edit their own balance.
