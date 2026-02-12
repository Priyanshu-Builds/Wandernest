# 🏕️ WanderNest – A Travel Accommodation Platform

**WanderNest** is an innovative full-stack platform that connects travelers with personalized lodging experiences globally. The system enables users to book stays, list accommodations, offer local experiences, and engage in a cultural exchange community — all within a secure and scalable application.
<img width="522" height="550" alt="Home-Page" src="https://github.com/user-attachments/assets/39240518-e7a5-4b03-8cbf-1955a2f78dd2" />

---

## 🎯 Project Aim

To develop a dynamic, secure, and intuitive platform for short-term rentals that promotes cultural exchange, trust, and global hospitality through a user-friendly digital marketplace.

---

## 📌 Abstract

WanderNest reimagines hospitality by creating a global community-driven marketplace where hosts can list accommodations, cars, or experiences, and guests can book based on personalized preferences. With features like couch-surfing, car rentals, and local activity listings, the platform delivers authentic travel experiences while ensuring safety, transparency, and accessibility.

---

## 🚀 Key Features

### ✅ Functional Requirements

- **User Registration & Authentication**
  - Sign up/login as guest or host
  - Email/password and social media integration

<img width="312" height="400" alt="Login" src="https://github.com/user-attachments/assets/1eb6e912-60e3-449e-87f3-7484b5f9231c" />
<img width="386" height="500" alt="SignUP" src="https://github.com/user-attachments/assets/9d56d682-f661-4f94-9422-61082a69c819" />



- **Property Listing Management**
  - Hosts can create, edit, and manage listings
  - Listings include images, description, amenities, calendar, and pricing

<img width="628" height="685" alt="Listing" src="https://github.com/user-attachments/assets/a4a90498-917a-4ec5-9c39-3a59336e2f9c" />
<img width="946" height="2132" alt="Listing-Details" src="https://github.com/user-attachments/assets/1fe07a4f-f751-46ac-a654-d71755dec0ca" />



- **Search & Booking**
  - Filter by location, price, availability, amenities
  - Real-time booking with calendar sync

<img width="642" height="436" alt="Search" src="https://github.com/user-attachments/assets/4d9acfa2-75dc-4678-99f0-f46651b2cbcd" />
<img width="583" height="2126" alt="Booking" src="https://github.com/user-attachments/assets/8e6ad0c4-1423-4afd-ba5f-aa8c31fa5d89" />



- **Secure Payment Processing**
  - Credit/debit cards, wallets, encrypted transactions
 
  <img width="683" height="516" alt="Patment" src="https://github.com/user-attachments/assets/8b99b36a-ae4f-49c3-a160-31736709c97a" />


- **Reviews & Ratings**
  - Two-way reviews between guests and hosts post-stay

- **Location Services**
  - GPS-based functionality for location-aware features
<img width="821" height="350" alt="Screenshot 2025-07-16 175615" src="https://github.com/user-attachments/assets/51175857-acae-40e9-ad61-8e9bf668cf01" />


- **Messaging System**
  - In-app chat between hosts and guests
  - Booking and notification alerts

- **Car Rentals**
  - Hosts or local vendors can list vehicles for rent
<img width="854" height="234" alt="Screenshot 2025-07-16 175610" src="https://github.com/user-attachments/assets/d16b0e15-5dec-45a6-ba21-b8bc72f9e500" />


- **Couch Surfing Support**
  - Option for hosts to offer free stays
  - Trust established through reviews and verification

- **Local Experience Listings**
  - Hosts can offer tours, cooking classes, or cultural activities

- **Community Building**
  - Local recommendations, forums, and cultural engagement

---

## ⚙️ Non-Functional Requirements

- **Performance**
  - High responsiveness with minimal load times
  - Scalable backend for high user volume

- **Security**
  - Encrypted user data and payments
  - Host verification and secure login

- **Reliability**
  - 99.9% uptime goal
  - Regular data backups and fail-safes

- **Scalability**
  - Horizontal scalability for traffic spikes
  - Efficient backend architecture using Express.js and MongoDB

- **Compliance**
  - GDPR-compliant handling of personal data
  - Follows local short-term rental regulations

- **Platform Independence**
  - Works across devices and browsers

- **Feedback & Updates**
  - Integrated feedback loop from users
  - Iterative updates based on analytics and user input

---

## 🛠️ Tech Stack

| Layer         | Tools / Technologies            |
|---------------|---------------------------------|
| **Frontend**  | React, JavaScript, HTML, CSS    |
| **Backend**   | Node.js, Express.js             |
| **Database**  | MongoDB Atlas                   |
| **Tools**     | Jira, Confluence, Zoho          |
| **Versioning**| Git, GitHub                     |
| **Design**    | Figma (optional)                |

---

## 📂 Project Structure

```

Wandernest/
├── client/         # React frontend
│   ├── public/
│   └── src/
├── server/         # Express backend
│   ├── models/
│   ├── routes/
│   └── index.js
├── .gitignore
├── README.md

````

---

## 📄 Environment Setup

### 🔧 Prerequisites

- Node.js & npm
- MongoDB Atlas account

### 📁 Environment Variables

In `/server/.env`, set:

```env
MONGO_URL=mongodb+srv://<username>:<password>@cluster0.mongodb.net/wandernest?retryWrites=true&w=majority
````

> ⚠️ Replace with your actual credentials. URL-encode special characters in the password.

---

## 🖥️ Running Locally

```bash
# Clone the repo
git clone https://github.com/Priyanshu-Builds/Wandernest.git
cd Wandernest

# Start Backend
cd server
npm install
node index.js

# Start Frontend
cd ../client
npm install
npm start
```

---

## 📊 Project Management Tools Used

* **Jira** – For Agile sprint planning, issue tracking
* **Confluence** – Documentation collaboration
* **Zoho** – Cost estimation and task tracking
* **Gantt Chart, PERT Chart, WBS** – Project planning and timeline visualization
* **COCOMO Model** – Used for software cost estimation (\~550 LOC)

---

## 🔮 Future Enhancements

* Payment gateway integration (e.g., Stripe, Razorpay)
* Admin dashboard for approval/analytics
* Booking calendar sync with Google Calendar
* Notifications via email/SMS
* Mobile app with React Native
* Advanced AI-based matching for accommodations

---

## 🧠 Use Case Diagram
<img width="1379" height="1694" alt="Use-Case" src="https://github.com/user-attachments/assets/656a79c0-4ca1-42eb-9614-c1bc531c5b0d" />

---

## 🧾 Cost Estimation (COCOMO)

* LOC: 550
* Mode: Organic
* Tools Used: Zoho
* Includes: Infrastructure, development time, risk buffer

---

> ⭐ If you like this project or found it useful, please consider giving it a star on GitHub!
