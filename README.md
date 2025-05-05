# Golf Club Rental App

A peer-to-peer platform where golfers can rent or lend golf clubs, similar to Uber or Airbnb but for golf gear.

## Features

- User authentication (Firebase)
- Add and browse available golf club listings
- View listings based on location
- Firebase integration for database and authentication
- Stripe-ready architecture for future payment integration
- Legal documents included (Privacy Policy & Terms of Service)

## Getting Started

### Prerequisites
- Node.js and npm
- Firebase project with Firestore and Authentication enabled

### Installation
```bash
npm install
npm start
```

### Firebase Setup
Update `firebase.js` with your own Firebase configuration:
```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_APP.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

## Deployment
You can deploy this app to:
- [Replit](https://replit.com)
- [Vercel](https://vercel.com)

## Legal
Includes:
- Privacy Policy
- Terms of Service

Found in `GolfClubRentalApp_LegalDocs.pdf`

## License
MIT
