# DocBook 🩺

### Doctor Appointment Booking Web Application

DocBook is a full-stack doctor appointment booking web application that allows patients to discover doctors, book appointments, manage their profiles, and track appointment history. Doctors can manage their profiles, appointments, and patient information through a dedicated dashboard.

---

## 🚀 Features

### 👤 For Patients

* Search and discover doctors
* Filter doctors by specialty
* Book doctor appointments
* View appointment history
* Manage personal profile
* Responsive user interface

### 👨‍⚕️ For Doctors

* Doctor dashboard with appointment statistics
* Manage professional profile
* View patient appointments
* Confirm or cancel appointments
* Manage appointment status

### 🔐 Authentication

* Role-based authentication
* Separate Doctor and Patient experiences
* Protected routes
* Form validation
* Login and registration functionality

---

## 🛠️ Tech Stack

### Frontend

* Next.js 14
* TypeScript
* Tailwind CSS
* shadcn/ui
* React Context API

### Backend

* JSON Server
* REST API
* Local JSON database

### Other Tools

* React
* Next.js App Router
* Responsive UI
* Toast Notifications

---

## 🏗️ Project Structure

```text
DocBook/
│
├── app/
│   ├── auth/
│   ├── doctor/
│   ├── profile/
│   ├── appointments/
│   ├── booking/
│   └── consultations/
│
├── components/
│   ├── ui/
│   ├── Navbar.tsx
│   ├── ProtectedRoute.tsx
│   └── ...
│
├── contexts/
│   └── AuthContext.tsx
│
├── hooks/
│
├── lib/
│   ├── api.ts
│   └── utils.ts
│
├── public/
│
├── styles/
│
├── db.json
├── middleware.ts
├── next.config.mjs
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Node.js 18+
* npm

### 1. Clone the repository

```bash
git clone https://github.com/jyottamahajan/doctor-booking-app.git
cd doctor-booking-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start JSON Server

Open a terminal and run:

```bash
npm run json-server
```

The mock backend will run on:

```text
http://localhost:3001
```

### 4. Start the Next.js application

Open another terminal:

```bash
npm run dev
```

The application will run on:

```text
http://localhost:3000
```

---

## 🔑 Demo Credentials

### Doctor Account

```text
Email: sarah@example.com
Password: password123
Role: Doctor
```

### Patient Account

```text
Email: john@example.com
Password: password123
Role: Patient
```

---

## 🔌 API Endpoints

The application uses JSON Server as a mock backend.

| Method | Endpoint            | Description        |
| ------ | ------------------- | ------------------ |
| GET    | `/doctors`          | Get doctors        |
| GET    | `/patients`         | Get patients       |
| GET    | `/appointments`     | Get appointments   |
| POST   | `/doctors`          | Create doctor      |
| POST   | `/patients`         | Create patient     |
| POST   | `/appointments`     | Book appointment   |
| PATCH  | `/appointments/:id` | Update appointment |

---

## 📱 Main Application Pages

### Patient

* Home
* Find Doctors
* Doctor Profile
* Book Appointment
* Appointments
* Prescriptions
* Profile

### Doctor

* Doctor Dashboard
* Appointments
* Patients
* Schedule
* Prescriptions
* Analytics
* Professional Profile

---

## 🎨 UI & Design

* Responsive design
* Modern medical application interface
* Dark theme support
* Reusable shadcn/ui components
* Toast notifications
* Form validation
* Protected dashboard routes

---

## 👥 Team Project

DocBook was developed as a **collaborative team project**.

My involvement included:

* Project coordination
* Requirement understanding
* Testing and project review
* Documentation
* Portfolio presentation

The core application development was handled collaboratively by the development team.

---

## 🔮 Future Improvements

* Real backend and production database
* Real-time appointment availability
* Online payment integration
* Video consultation integration
* Email/SMS appointment notifications
* Doctor verification system
* Cloud deployment
* Advanced analytics

---

## 📄 License

This project is maintained as a team project for learning, development, and portfolio demonstration purposes.

---

### ❤️ Built with Next.js, TypeScript & Tailwind CSS
