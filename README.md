# 🌱 AgriTrack

AgriTrack is a modern agricultural management platform designed to help farmers and agribusinesses track crops, machinery, sales, and sensor data in real time.  
The project integrates **.NET API**, **relational and NoSQL databases**, **React/Blazor frontend**, and **AWS cloud services** to provide a complete end-to-end solution.

---

## 📌 Project Overview

AgriTrack enables farmers to:
- Manage crops, machinery, and sales records.
- Collect and store real-time sensor data (humidity, temperature, etc.).
- View statistics and insights via an interactive dashboard.
- Receive automatic alerts for low moisture or critical events.
- Store and retrieve crop images using AWS S3.

This repository follows a **6-week learning and development plan** with weekly deliverables and mini-projects.

---

## 🗂 Weekly Roadmap

### **Week 1 – Fundamentals & Setup**
- Create GitHub repository with project description.
- Set up an empty ASP.NET Core API.
- Implement initial CI/CD pipeline using GitHub Actions.
- **Mini-project:** To-Do List API (CRUD with Git).

### **Week 2 – REST API + Relational DB**
- CRUD endpoints for Crops, Machinery, and Sales.
- Connect to PostgreSQL using Entity Framework Core.
- Document API with Swagger.
- **Mini-project:** Inventory Control API with SQL Server.

### **Week 3 – NoSQL DB + Authentication**
- Add MongoDB for sensor data storage.
- Implement JWT authentication for farmers and admins.
- **Mini-project:** Event Log API with MongoDB.

### **Week 4 – Frontend**
- React or Blazor UI:
  - Crop statistics dashboard.
  - Sales registration form.
  - Map or list of plots.
- **Mini-project:** React frontend consuming a public API.

### **Week 5 – AWS + DevOps**
- Deploy API to AWS Elastic Beanstalk or ECS.
- Configure RDS (PostgreSQL) and S3 (images).
- Expand CI/CD with GitHub Actions for deployments.
- **Mini-project:** AWS S3 Image Gallery API.

### **Week 6 – Messaging Queues + Testing**
- Integrate RabbitMQ or AWS SQS for automated alerts.
- Implement unit and integration testing.
- Prepare demo and technical documentation.
- **Mini-project:** Email sending service with queues.

---

## 🏗 Architecture Overview

**Backend:**
- ASP.NET Core API
- Entity Framework Core (PostgreSQL)
- MongoDB for sensor data
- JWT Authentication
- RabbitMQ or AWS SQS for alerts

**Frontend:**
- React (Vite + Tailwind) or Blazor
- REST API consumption
- Interactive dashboards and forms

**Cloud & DevOps:**
- AWS Elastic Beanstalk or ECS
- AWS RDS (PostgreSQL), AWS S3 (images)
- GitHub Actions (CI/CD)
- Docker for containerization

---

## 🚀 Tech Stack

| Layer         | Technology |
|--------------|------------|
| Backend API  | ASP.NET Core |
| Relational DB| PostgreSQL (AWS RDS) |
| NoSQL DB     | MongoDB (Atlas or AWS DocumentDB) |
| Auth         | JWT / ASP.NET Identity |
| Frontend     | React (Vite + Tailwind) or Blazor |
| Messaging    | RabbitMQ or AWS SQS |
| Cloud        | AWS ECS / Elastic Beanstalk, AWS S3 |
| CI/CD        | GitHub Actions |

---

## 📚 Learning Goals
- Full-stack development with **.NET + React**.
- Working with **relational and NoSQL databases**.
- Implementing **authentication & authorization**.
- Deploying to **AWS with CI/CD**.
- Using **message queues** for event-driven architecture.
- Writing **unit and integration tests**.

---

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
