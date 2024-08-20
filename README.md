# 🩸 BloodBridge

Welcome to **BloodBridge**! This project is a comprehensive platform designed to manage and facilitate blood donation activities. It connects donors, hospitals, and organizations through a seamless communication system powered by MongoDB and a RESTful API.

---

## 🚀 Features

- **Donor Management:** Register and manage blood donors with ease.
- **Hospital Integration:** Hospitals can request blood donations and manage inventory.
- **Organization Coordination:** Non-profits and other organizations can manage blood donation drives and communication.
- **RESTful API:** Efficient and secure communication between the client and server.
- **MongoDB:** Reliable and scalable database for managing large datasets.

---


## 🔧 Technologies Used

- **Frontend:**
  - React.js 
  - CSS / SCSS for styling

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB for the database
  - RESTful API for server-client communication

---

## 📂 Project Structure

```bash
bloodbridge/
├── client/             # Frontend files (if applicable)
│   └── ...
├── config/             # Configuration files (db, jwt, etc.)
│   └── ...
├── controllers/        # API controllers
│   └── ...
├── middlewares/        # Custom middlewares
│   └── ...
├── models/             # Mongoose models
│   └── ...
├── routes/             # API routes
│   └── ...
├── .gitignore          # Git ignore file
├── package-lock.json   # Package lock file
├── package.json        # Package file
└── server.js           # Entry point for the server
