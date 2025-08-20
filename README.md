Future Me – Digital Notes to Your Future Self
Future Me is a web application that allows users to write personal notes, attach images, and lock them to be unlocked on a future date. It also offers mood based motivational support to help users stay positive and inspired. The app is fully private only the user can view their notes.

Features
Create Notes: Write text notes to your future self.
Unlock Notes on a Specific Date: Lock notes until a chosen future date.
Add Images: Optionally attach an image to your note.
Mood Support: Select your current mood; the app will provide motivational messages if a negative emotion is detected.

Analytics Dashboard:
Total notes, locked and unlocked notes
Active days and weekly interactions
Notes activity chart showing engagement over time
Privacy-Focused: Notes are stored securely in Firebase Firestore; not even admins can view them.
Real-Time Updates: Changes are reflected instantly on the dashboard and notes list.

![1.png](futureme/README.md/1.png)


Tech Stack
Frontend: HTML, Tailwind CSS, JavaScript
Icons: Phosphor Icons
Backend / Database: Firebase Authentication & Firestore
Fonts: Inter (Google Fonts)


Usage
"https://github.com/aishwaryar1199-dotcom/futureme.git"

Open index.html in a browser.
Start creating notes:
Enter your note text.
Choose an unlock date.
Select your current mood.
Optionally upload an image.
Click Lock Note.
View unlocked and locked notes in the right panel.
Track your note interactions and mood stats on the dashboard.

How It Works
Notes are stored in Firebase Firestore under each user’s private collection.
When the unlock date is reached, the note appears in the Unlocked Notes section.
A basic sentiment check detects negative emotions and displays motivational messages.
Dashboard metrics and charts update in real-time using Firebase onSnapshot.

Roadmap / Future Improvements

Add user accounts for persistent login across devices.
Enable editing and deleting notes.
Add mood history trends with advanced analytics.
Integrate push notifications when a note is unlocked.
