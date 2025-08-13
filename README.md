# 🛍️ Demo Store (Full Stack)

Welcome to **Demo Store**, now a **full stack e-commerce** project! This version uses modern technologies for both frontend and backend, including authentication and PostgreSQL database integration.

👉 [Check out the live demo here!](https://demostore-rho.vercel.app/)

---

## ✨ Features

✅ Responsive and modern layout
✅ Product listing from database
✅ Add products to cart
✅ Automatic total price calculation
✅ User authentication (JWT)
✅ Order management
✅ PostgreSQL integration
✅ TypeScript everywhere
✅ User-friendly interface

---

## 🧰 Technologies Used

![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)  
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)  
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)  
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)  
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jwt&logoColor=white)

---

## 📸 Screenshots

> ![screenshot](./img/screenshot.png)

---

## 🚀 How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/demo-store.git

   ```

2. Install dependencies:
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install

   ```
3. Configure PostgreSQL and Prisma:

   - Set up your PostgreSQL database
   - Update `backend/.env` with your database URL
   - Run Prisma migrations:

   ```bash
   cd backend
   npx prisma migrate dev
   ```

4. Start the backend server:

   ```bash
   npm run dev
   ```

5. Start the frontend:
   ```bash
   cd ../frontend
   npm run dev
   ```

6. Open the app in your browser:
Frontend: http://localhost:5173
Backend API: http://localhost:3000

---

## 🗂️ Project Structure
```
backend/
   src/
   package.json
   tsconfig.json
   ...
frontend/
   src/
   package.json
   tsconfig.json
   ...
```

---