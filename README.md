## **Anonymous Student Feedback System**  

### **Overview**  
The **Anonymous Student Feedback System** is a web application designed to collect and analyze anonymous feedback from students regarding courses, instructors, and their overall learning experience. This system ensures **student anonymity** while providing **valuable insights** for instructors and administrators.  

This project is built using the **MERN stack** (**MongoDB, Express.js, React.js, Node.js**) for **scalability** and **flexibility**.  

---

## **Features**  

✅ **Student Anonymity:** Feedback submissions are **encrypted using SHA-256**, ensuring no student identities are exposed.  

✅ **Feedback Categories:** Students can submit feedback on multiple aspects, such as **teaching quality, course content, and overall satisfaction**.  

✅ **Real-time Data Visualization:** Feedback results are displayed using **Chart.js** for **interactive graphs and charts**, making analysis easier.  

✅ **User Roles:**  
- 🎓 **Student** – Can submit feedback **anonymously**.  
- 👨‍🏫 **Instructor/Admin** – Can view **aggregated feedback summaries** but **cannot trace them back** to individual students.  

✅ **Secure Authentication:** Implements **JWT-based authentication** and **role-based access control**.  

✅ **Responsive Design:** The UI is **fully responsive**, working on **mobile, tablet, and desktop devices**.  

---

## **Technologies Used**  

### **Frontend:**  
- ⚛️ **React.js** – For building a **dynamic user interface**  
- 📊 **Chart.js** – For displaying **interactive feedback data**  
- 🎨 **HTML5 & CSS3** – For **structuring and styling**  

### **Backend:**  
- 🖥️ **Node.js & Express.js** – For handling **server-side operations** and **API requests**  
- 🛢️ **MongoDB** – For storing **feedback data securely**  
- 🔐 **SHA-256 Encryption** – To ensure **student anonymity**  

### **Additional Tools/Libraries:**  
- 🔄 **Axios** – For handling **API requests**  
- 🔑 **JWT** – For **secure authentication**  
- ⚙️ **dotenv** – For managing **environment variables**  

---

## **Project Setup**  

### **Prerequisites:**  
- **Node.js** (v14 or higher)  
- **MongoDB** (Local instance or **MongoDB Atlas**)  
- **NPM** (Comes with Node.js)  

### **Installation Steps:**  

#### **1️⃣ Clone the Repositories**  
```bash
# Frontend
git clone https://github.com/your-username/feedback-system-client.git

# Backend
git clone https://github.com/your-username/feedback-system-server.git
```

#### **2️⃣ Install Dependencies**  
```bash
# Backend setup
cd feedback-system-server
npm install

# Frontend setup
cd ../feedback-system-client
npm install
```

#### **3️⃣ Configure Environment Variables**  

Create a `.env` file inside the **backend** directory and add the following:  

```
MONGO_URI=your_mongo_database_url
JWT_SECRET=your_jwt_secret_key
FRONTEND_URL=https://your-frontend-url.vercel.app
```

#### **4️⃣ Run the Project**  

In **one terminal window**, start the **backend server**:  
```bash
cd feedback-system-server
npm start
```

In **another terminal window**, start the **frontend**:  
```bash
cd feedback-system-client
npm start
```

#### **5️⃣ Open the Application**  
Go to: **`http://localhost:3000`**  

---

## **Usage**  

### **🎓 Student Role:**  
- Login with student credentials  
- Select a course and submit **anonymous feedback**  
- Feedback is securely stored without revealing identity  

### **👨‍🏫 Instructor/Admin Role:**  
- Login with instructor/admin credentials  
- Access a **dashboard with real-time feedback analytics**  
- Use the **insights to improve course quality**  

---

## **Challenges Faced**  

🚧 **Frequent Changes:** Continuous feedback from teachers required a **flexible frontend & backend design**.  

📊 **Selecting the Right Charting Library:** After testing multiple libraries, **Chart.js** was chosen for its **ease of use and interactivity**.  

🔐 **Ensuring Anonymity:** **SHA-256 encryption** was used to **securely store** feedback data while maintaining **anonymity**.  

---

## **Future Improvements**  

🚀 **Advanced Analytics:** Implement **sentiment analysis** to classify feedback as **positive, neutral, or negative**.  

📩 **Email Notifications:** Notify instructors when **new feedback is received**.  

📤 **Export Feedback:** Allow **exporting feedback** to **CSV or PDF** for **offline analysis**.  

🎨 **UI Enhancements:** Improve **UX/UI** for a **better user experience**.  

---

## **Contributing**  

🤝 Contributions are **welcome**! If you'd like to improve the project:  

1️⃣ **Fork** the repository  
2️⃣ **Create a feature branch**  
3️⃣ **Commit your changes**  
4️⃣ **Submit a Pull Request**  

---

## **License**  

📜 This project is licensed under the **MIT License**. See the **LICENSE** file for more details.  

---

### **📌 Notes:**  
- **Frontend Deployed URL:** [https://feedback-system-client-2oay1anp9-ajays-projects-b96f1c0e.vercel.app/](https://feedback-system-client-2oay1anp9-ajays-projects-b96f1c0e.vercel.app/)  
- **Backend Deployed URL:** [https://feedback-system-server-nzt4.onrender.com](https://feedback-system-server-nzt4.onrender.com)  

---

This README provides a **clear, professional, and structured** documentation for your project. Let me know if you need **any tweaks!** 🚀
