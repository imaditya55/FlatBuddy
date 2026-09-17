
# 🏠 Roommate Matcher – Smart Compatibility Based Matching System

A full-stack web application that helps users find compatible roommates based on lifestyle preferences such as sleep schedule, study routine, cleanliness, noise tolerance, budget range, habits, and hostel location.

Instead of random suggestions, the system calculates a smart compatibility score and explains why two users are a good match.

---

## 🚀 Features

### ✅ User Authentication
- Secure signup & login using JWT

### ✅ Preference Based Matching
Users set:
- Sleep time
- Study time
- Cleanliness level
- Noise tolerance
- Food preference
- Budget range
- Smoking & drinking habits
- Hostel block

### ✅ Smart Matching Algorithm
- Calculates compatibility score
- Converts it into percentage
- Shows match reasons (same routine, budget overlap, etc.)

### ✅ Clean UX Flow
- First login → fill preferences
- Later logins → directly see matches
- Edit preferences anytime

---

## 🛠 Tech Stack

### Frontend
- React
- Tailwind CSS
- React Router

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)

### Authentication
- JWT (JSON Web Tokens)

---

## 📊 How Matching Works

Each user is scored based on:

- Lifestyle similarity
- Budget overlap
- Routine compatibility
- Location match
- Habit tolerance

The app returns:
- Compatibility percentage
- Clear match reasons

---

## 🖥 Setup Instructions

### 1️⃣ Clone the repo

```bash
git clone https://github.com/yourusername/roommate-matcher.git
cd roommate-matcher

2️⃣ Install backend dependencies
cd backend
npm install

3️⃣ Install frontend dependencies
cd frontend
npm install

4️⃣ Create .env file in backend
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000

5️⃣ Run backend
npm start

6️⃣ Run frontend
npm run dev

📌 Future Improvements

Real-time chat between matched users

Match filters (budget, location, %)

Compatibility progress bar

ML-based recommendations

Profile completeness tracking

🎯 Why This Project?

This project focuses on:

✔ Real world problem
✔ Smart algorithmic matching
✔ Clean full-stack architecture
✔ Scalable design

👨‍💻 Author

Your Name

Feel free to connect and improve this project!

⭐ If you like this project, give it a star!


---

# 📁 Bonus (professional touch – optional)

Create a file:

### `.env.example`

```env
MONGO_URI=
JWT_SECRET=
PORT=
