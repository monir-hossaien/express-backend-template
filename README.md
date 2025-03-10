# 🩺 **Doctor Finder Website**

The **Doctor Finder Website** is a comprehensive platform where patients can search for doctors based on specialization, location, experience, and ratings. Patients can easily book appointments, view doctor profiles, and leave reviews. Doctors can manage their profiles and availability, while admins have control over users, doctor approvals, and appointments.

---

## 🚀 **Features**

### **User Authentication**
- Secure login & registration for **Patients**, **Doctors**, and **Admins** using **JWT** and **bcrypt**.

### **Doctor Search**
- Search for doctors based on **specialization**, **location**, **experience**, and **ratings**.
- View doctor **profiles** with detailed information.

### **Appointment Booking**
- Patients can **book appointments** with doctors based on available time slots.
- Real-time availability and booking confirmation.

### **Reviews & Ratings**
- **Patients** can rate doctors and leave **feedback** based on their consultation experience.

### **Admin Dashboard**
- **Admins** can manage users, approve/reject doctor profiles, and oversee appointments and reviews.

### **Notifications**
- **Automated email/SMS** notifications for appointment confirmations and reminders.

---

## 🛠️ **Tech Stack**

- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Authentication**: JWT & bcrypt
- **File Storage**: Multer & Cloudinary (optional for image uploads)
- **Notifications**: SendGrid (email) / Twilio (SMS)

---

## ⚙️ **Setup & Installation**

### **Prerequisites**
- **Node.js** (v14 or higher)
- **MongoDB** (local or cloud)
- **Cloudinary** account (for image uploads) *(optional)*
- **SendGrid** or **Twilio** account *(for email/SMS notifications)*

---
Install Dependencies
Install the backend and frontend dependencies:


npm install

Configure Environment Variables
Create a .env file in the backend directory and add your environment variables:

env
Copy
Edit
PORT=5000
---
MONGO_URI=your_mongo_database_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
SENDGRID_API_KEY=your_sendgrid_api_key
---
Run the Project
Start Backend Server

npm run server
Start Frontend (React App)
Navigate to the client folder and run:


cd client
npm start
---
📄 Usage
For Patients:
Register and login to create an account.
Search doctors by filtering options such as specialization, location, and ratings.
Book appointments based on available slots.
Leave reviews and ratings after consultation.

---
For Doctors:
Create and manage your profile with details like specialization, experience, and consultation fees.
Set available time slots and manage bookings.
---
For Admins:
Approve or reject doctor profiles.
Manage users (patients and doctors).
Monitor appointments and reviews.
---
📝 License
This project is licensed under the MIT License - see the LICENSE file for more details.

👨‍💻 Contributors
Monir Hossain
LinkedIn | GitHub
📸 Screenshots

🖋️ Acknowledgements
MERN Stack for full-stack development.
MongoDB for database management.
Cloudinary for file uploads (optional).
SendGrid / Twilio for notifications.


