# 🔐 Authentication Backend APIs

A robust and production-ready authentication API featuring secure JWT-based authentication, email verification, password recovery, and 2FA support. Built with **Node.js, Express, TypeScript, MongoDB, Zod, and Resend**.

<img src="https://img.shields.io/badge/node%20js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/express%20js-000000?style=for-the-badge&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" /> <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" />

---

## ✨ **Key Features**  

**1. User Authentication**  
- 🗄️ Database setup with MongoDB  
- 🔐 Secure signup & login endpoints  
- 📧 Email verification with Resend  
- 🔄 Forgot & reset password flow  

**2. Session & Security**  
- 🛡️ JWT-based access & refresh tokens  
- 🖥️ Session management & logout  
- 📲 Two-factor authentication (2FA)  
- 📉 Rate limiting for security 

---

## 🛠️ **Getting Started**  

### **1. Prerequisites**  
- Node.js (v18+)  
- MongoDB Atlas or local instance  
- Resend API key (for email)  

### **2. Setup**  

1. **Clone the repository**  
   ```sh
   git clone https://github.com/AmanKrSahu/advance-auth-api.git
   cd advance-auth-api
   ```

2. **Install dependencies**  
   ```sh
   npm install
   ```

3. **Configure environment variables**  
   Rename `.env.example` to `.env` and update:  
   ```env
   PORT=8000
   NODE_ENV=development

   MONGO_URI="mongodb+srv://<username>:<password>@<cluster>.mongodb.net/mern_db"

   APP_ORIGIN="http://localhost:3000"

   JWT_SECRET="your_jwt_secret"
   JWT_EXPIRES_IN="15m"
   JWT_REFRESH_SECRET="your_refresh_secret"
   JWT_REFRESH_EXPIRES_IN="30d"

   RESEND_API_KEY="your_resend_api_key"
   MAILER_SENDER="onboarding@resend.dev"
   ```

4. **Run the server**  
   ```sh
   npm run dev  # Development
   npm start    # Production
   ```

---

## 🚀 Need Help??

Feel free to contact me on [Linkedin](https://www.linkedin.com/in/amankrsahu)

[![Instagram URL](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/itz.amansahu/) &nbsp; [![Discord URL](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](discordapp.com/users/539751578866024479)