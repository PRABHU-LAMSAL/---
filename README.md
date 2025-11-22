# User Details Web App

A modern web application for adding and displaying user details using Firebase Realtime Database.

## Features

- ✅ Add user details (name, email, phone, address, notes)
- ✅ View all details in real-time
- ✅ Delete details
- ✅ Beautiful, responsive UI
- ✅ Real-time synchronization with Firebase

## Setup Instructions

1. **Open the app**: Simply open `index.html` in a modern web browser (Chrome, Firefox, Edge)

2. **Firebase Setup**: The Firebase configuration is already included in `firebase-config.js`. Make sure your Firebase Realtime Database is set up and rules allow read/write access.

3. **Database Rules**: Update your Firebase Realtime Database rules in the Firebase Console:
   ```json
   {
     "rules": {
       "userDetails": {
         ".read": true,
         ".write": true
       }
     }
   }
   ```

## File Structure

- `index.html` - Main HTML structure
- `styles.css` - Styling and responsive design
- `firebase-config.js` - Firebase configuration and initialization
- `app.js` - Application logic for adding and displaying details

## Usage

1. Fill in the form on the left side with user details
2. Click "Add Details" to save to Firebase
3. View all saved details on the right side
4. Click the delete button (🗑️) to remove any detail
5. Use the refresh button to reload details

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (ES6+)
- Firebase Realtime Database
- Firebase Analytics

## Browser Compatibility

Works best with modern browsers that support ES6 modules:
- Chrome (latest)
- Firefox (latest)
- Edge (latest)
- Safari (latest)

