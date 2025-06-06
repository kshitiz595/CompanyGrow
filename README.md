# 🚀 Employee Growth & Performance Platform

**A full-stack web application to help organizations nurture employee growth through training, project allocation, and real-time performance rewards.**

**This website has already been deployed on:**  
**[https://companygrow.onrender.com](https://companygrow.onrender.com)** *(hosted on Render)*  
**Login credentials are available under step 4 (Initialize the Application with Dummy Data).**


**Developed by:**  
- **Mahaswin**  
- **Cherish**  
- **Srivardhan**


Built with the **MERN Stack**: MongoDB, Express.js, React.js, and Node.js.

---

## 📁 Project Structure

root/  
│  
├── backend/ # Express.js server & MongoDB models  
│ └── package.json  
│  
├── frontend/ # React.js client application  
│ └── package.json  
│   
└── README.md  


---

## 🛠️ Getting Started

### 1. Clone the Repository

git clone https://github.com/Persive07/CompanyGrow.git  
cd CompanyGrow


### 2. Install Dependencies

cd backend  
npm install

Open a new terminal and run:

cd frontend  
npm install

### 3. Environment Variables

Create a `.env` file in the `backend/` folder and add the following:  

MONGO_URI= 
PORT=  
JWT_SECRET=  
STRIPE_SECRET_KEY=  
CLIENT_URL=  

Create a `.env` file in the `frontend/` folder and add:   

REACT_APP_API_BASE_URL=  
REACT_APP_STRIPE_PUBLISHABLE_KEY=  

---

### 4.(Optional : Only when using your own database) Initialize the Application with Dummy Data

To add dummy data for a better developer experience, run:  

cd backend  
node seeds/user.seed.js  
node seeds/course.seed.js  
node seeds/projects.seed.js  

---

## 🧑‍💻 Dummy User Credentials

| Username (Email)                  | Password    | Role      |
|-----------------------------------|-------------|-----------|
| emily.johnson@example.com         | password123 | employee  |
| michael.thompson@example.com      | password123 | manager   |
| james.walker@example.com          | password123 | admin     |

> **Note:** These credentials are for development and demo purposes only. Always use strong, unique passwords in production.

---

> **Initializing with dummy data ensures a smooth onboarding experience for new developers and showcases the platform’s features.**


---

### 5. Run the Application

**Start Backend**

cd backend  
npm start  


**Start Frontend (Port 3000)**

cd frontend  
npm start  


---

## 🧩 Features

- **👨‍💼 Role-based access:** Admin, Manager, Employee
- **📚 Course creation, enrollment, and tracking**
- **🏆 Badge rewards for course and project completion**
- **📊 Performance metrics and progress tracking**
- **📈 Analytics dashboards with Chart.js visualizations**
- **📄 Exportable reports of performance visualizations using jsPDF**
- **💸 Stripe payment integration for bonuses**
- **📁 Real-time project assignment and status updates**

---

## 📦 Tech Stack

- **Frontend:** React.js, React Router, Axios, Chart.js, jsPDF
- **Backend:** Express.js, Node.js
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT-based authentication
- **Payments:** Stripe API Integration

---

## 💡 Future Enhancements

- **📧 Email notifications**
- **🗓️ Gantt chart for project timelines**
- **🧠 AI-based skill recommendations**

---

## 📊 Visualizations & Reports

- **Employee performance visualized using Chart.js**
- **Exportable PDF reports generated with jsPDF**

---

## 📄 License

This project is licensed under the MIT License.
