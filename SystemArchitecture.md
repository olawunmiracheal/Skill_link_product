# 🧱 System Architecture – Skill Link

## ⚙️ Overview
Skill Link is designed as a **mobile-first, cloud-based platform** that connects users with verified artisans.  
The architecture focuses on **scalability, security, and smooth communication** between clients and artisans.

---

## 🖥️ Frontend
- **Technology:** React Native  
- **Purpose:** To provide a seamless cross-platform experience on Android and iOS devices.  
- **Responsibilities:**  
  - Display artisan profiles and job listings  
  - Handle user input and navigation  
  - Manage chat interface and booking flow  

---

## ⚙️ Backend
- **Technology:** Node.js with Express.js  
- **Purpose:** Acts as the brain of the platform, handling all logic, APIs, and security.  
- **Responsibilities:**  
  - User authentication and authorization  
  - API endpoints for data exchange  
  - Payment processing (escrow logic)  
  - Job tracking and notification management  

---

## 🗄️ Database
- **Technology:** MongoDB (NoSQL)  
- **Purpose:** Stores and manages all data in flexible collections.  
- **Data Stored:**  
  - User profiles (clients and artisans)  
  - Job records and payment history  
  - Ratings, reviews, and feedback  
  - Verification documents  

---

## 🔄 Component Communication
1. **Frontend → Backend:**  
   - Sends API requests for login, search, booking, and payments.  
2. **Backend → Database:**  
   - Reads/writes data to MongoDB.  
3. **Backend → Payment Gateway (Paystack/Flutterwave):**  
   - Handles secure transactions and escrow management.  
4. **Backend → Firebase (Notifications):**  
   - Sends job status updates and reminders to users.  

---

## 🧩 Technical Flow Diagram (Conceptual)




