# AirHaven

AirHaven is a modern vacation rental platform inspired by Airbnb, built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). Users can browse listings, book stays, upload property images, and make secure payments via Stripe. The app includes authentication, responsive design, and is deployed for live access.

---

## Features

- Browse and search rental listings
- User authentication (signup/login)
- Upload property images
- Book and manage reservations
- Secure payment integration via Stripe
- Responsive design for mobile and desktop
- Admin panel for managing listings (optional)

---

## Tech Stack

- **Frontend:** React.js, CSS / Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payments:** Stripe
- **Deployment:** Vercel / Heroku
- **Image Storage:** Cloudinary

---

## Installation & Setup

1. **Clone the repository**  
```bash
git clone https://github.com/Shivam8465/AirHaven.git
cd AirHaven
Install dependencies

For backend:
cd api
npm install


For frontend:
cd ../client
npm install


Set up environment variables
Create a .env file in the api folder and add:
PORT=5000
DB_URL=mongodb://127.0.0.1:27017/airhaven
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key


Run the app
Start backend:
cd api
npm run dev


Start frontend:
cd ../client
npm start


Author

Shivam Singh
