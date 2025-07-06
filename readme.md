# 🧾 InvoiceApp Server

A powerful backend service for managing client invoices, authentication, file uploads, email notifications, and more — built with Node.js, Express, and MongoDB.

---

## 🚀 Tech Stack

| Layer        | Technology                       |
|--------------|----------------------------------|
| Runtime      | Node.js (v16.13.1)               |
| Framework    | Express                          |
| Database     | MongoDB (via Mongoose ORM)       |
| Auth         | JWT (JSON Web Tokens)            |
| Uploads      | Multer + Express Formidable      |
| Notifications| Vonage SMS, Nodemailer Email     |
| Validation   | Validator.js                     |
| Utility Libs | dotenv, bcrypt, cors, morgan     |

---

## 📦 Features

- 🔐 User authentication with JWT
- 🧾 Invoice management APIs
- 📁 Secure file uploads (PDF, images)
- 📧 Email notifications via Nodemailer
- 📲 SMS notifications via Vonage
- ✅ Input validation with `validatorjs`
- 📂 Clean MVC architecture
- 🧪 Easy development with `.env` support
- 🛠️ Modular and production-ready

---

## 📁 Project Structure


---

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/kailash6962/invoiceappserver.git
cd invoiceappserver
```

### 2. Install dependencies
```
npm install
```

### 3. Configure Environment Variables
```
PORT=8000
MONGODB_URL=mongodb://localhost:27017/invoiceapp
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
VONAGE_API_KEY=your_api_key
VONAGE_API_SECRET=your_api_secret
```

### 4. Run the Server
```
npm start
```
