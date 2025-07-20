# 💼 CareerLinker – Job Portal Application

CareerLinker is a full-stack job portal web application that connects job seekers with recruiters. It provides a seamless platform for students to search and apply for jobs, while recruiters can post openings, manage applicants, and streamline the hiring process. Built with React.js, Node.js, Express, MongoDB, and Redux.

## 🚀 Features

### 👤 User Roles
- **Students**: Browse jobs, apply, and track applications.
- **Recruiters (Admins)**: Post jobs, view applicants, manage companies.

### 🛠️ Core Functionalities
- Authentication & Authorization (JWT, Cookies)
- Role-based access control (Student / Recruiter)
- Job listing, filtering & search
- Resume submission & profile management
- Company creation and job posting (for recruiters)
- Logout functionality for both users

## 🧰 Tech Stack

| Frontend        | Backend         | Database    | Other Tools          |
|----------------|------------------|-------------|-----------------------|
| React.js        | Node.js          | MongoDB     | Redux Toolkit         |
| Tailwind CSS    | Express.js       |             | Axios, Vite           |
| React Router    | REST APIs        |             | Cloudinary (uploads)  |
| Toast/Sonner    | JWT Auth         |             | Nodemon, Dotenv       |

## 🔐 Environment Variables

### Backend `.env`
```
PORT=8000
MONGO_URL=your_mongodb_connection
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
```

## 🖼️ UI Preview & Interface Highlights

### Home page
<img width="1900" height="936" alt="Screenshot 2025-07-20 170315" src="https://github.com/user-attachments/assets/dd2dfab8-d01c-4767-9c35-5850c590b22b" />

### Signup page
<img width="1403" height="782" alt="Screenshot 2025-07-20 170421" src="https://github.com/user-attachments/assets/fca0eed6-5066-4355-a855-23366228b910" />


## 🧠 Key Learnings & Skills

- Full-stack Web Development
- RESTful API Design
- Role-based Authentication (JWT)
- State Management using Redux Toolkit
- File uploads with Cloudinary
- Responsive UI with Tailwind CSS
- Frontend/backend integration
- Error handling and user notifications

## ✨ Future Improvements

- Resume parsing & scoring
- Admin dashboard with analytics
- Email notifications
- Pagination and search optimization
- Deployment on Render/Vercel
