# Poker-Club-Website

# 🃏 Poker Club Leaderboard  

A web application to track and rank poker players based on game results. Built with **Express.js, MongoDB, React.js, and WebSockets** for real-time updates.  

## 🚀 Features  
✅ Player registration & profiles  
✅ Admin authentication (JWT-based)  
✅ Game result submission  
✅ Real-time leaderboard updates (Socket.io)  
✅ Data visualization with charts  
✅ Mobile-friendly UI  

## 🛠 Tech Stack  
- **Frontend:** React.js (Next.js), Tailwind CSS  
- **Backend:** Express.js, Node.js  
- **Database:** MongoDB (Mongoose) / PostgreSQL (Prisma)  
- **Authentication:** JWT, bcrypt.js  
- **Real-time:** WebSockets (Socket.io)  
- **Deployment:** Vercel (frontend), Railway/Render (backend)  

## 📂 Project Structure  
```
📦 poker-club-leaderboard  
├── backend/  
│   ├── controllers/   # API logic  
│   ├── models/        # Database schemas  
│   ├── routes/        # Express API routes  
│   ├── middleware/    # Authentication & security  
│   ├── server.js      # Main Express server  
│  
├── frontend/  
│   ├── src/  
│   │   ├── components/  # React components  
│   │   ├── pages/       # Leaderboard & profiles  
│   │   ├── context/     # State management  
│   │   ├── App.js       # Main React app  
│  
└── README.md  
```

## 🏗️ Installation  
### **1️⃣ Clone Repository**  
```bash
git clone https://github.com/yourusername/poker-club-leaderboard.git
cd poker-club-leaderboard
```

### **2️⃣ Backend Setup**  
```bash
cd backend
npm install
cp .env.example .env  # Add your environment variables
npm start
```

### **3️⃣ Frontend Setup**  
```bash
cd frontend
npm install
npm start
```

## 🔥 API Routes (Express.js)  
| Method | Endpoint         | Description           |
|--------|----------------|----------------------|
| `POST` | `/register`     | Create admin account |
| `POST` | `/login`        | Authenticate admin   |
| `POST` | `/players`      | Add a new player     |
| `GET`  | `/leaderboard`  | Fetch rankings       |
| `POST` | `/games`        | Submit game result   |

## 🚀 Deployment  
- **Frontend:** Vercel  
- **Backend:** Railway/Render  
- **Database:** MongoDB Atlas / Supabase  

## 🙌 Contributing  
1. Fork the repo  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m "Add new feature"`)  
4. Push to your branch (`git push origin feature-name`)  
5. Open a Pull Request  

## 📜 License  
MIT License © 2025 Sedahoo 

---

Let me know if you want any modifications! 🚀
