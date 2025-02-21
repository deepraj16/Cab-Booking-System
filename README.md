
# 🚖 Cab Booking System

## 🌟 Overview
This is a **Cab Booking System** built using **Spring Boot**. It allows users to book cabs, manage ride details, and track their bookings efficiently.

---
![image](https://github.com/user-attachments/assets/54d0b4f0-db3a-49e2-a74a-f5fd2e496208)


## ✨ Features
- 🔐 User authentication and authorization
- 🚕 Booking cabs based on availability
- 📜 Ride history and fare calculation
- 🛠️ Admin panel for managing drivers and rides

## 🛠️ Technologies Used
- **Backend:** Spring Boot, Hibernate, Spring Security
- **Database:** PostgreSQL / MySQL
- **Build Tool:** Maven / Gradle
- **Deployment:** Render

## ⚡ Prerequisites
Before running the project, ensure you have the following installed:
- ☕ Java 17 or later
- 🏗️ Maven / Gradle
- 🗄️ PostgreSQL / MySQL (if using a database)
- 🖥️ Git

## 🚀 Installation and Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/deepraj16/Cab-Booking-System.git
cd cab-booking-system
```

### 2️⃣ Configure the Database
Update `application.properties`  with your database credentials:
```properties
spring.datasource.url=jdbc:postgresql://your-db-host:5432/your-database
spring.datasource.username=your-username
spring.datasource.password=your-password
```


### 1️⃣ Push Code to GitHub
Ensure your code is pushed to GitHub:
```sh
git add .
git commit -m "Initial commit"
git push origin main
```

### 2️⃣ Deploy on Render
1. Go to [Render](https://render.com/).
2. Click on **New Web Service**.
3. Connect your GitHub repository.
4. Set the **Build Command** (if using Maven):
   ```sh
   ./mvnw clean install
   ```
5. Set the **Start Command**:
   ```sh
   java -jar target/cab-booking-system.jar
   ```
6. Choose an appropriate database service if required.
7. 🚀 Deploy the application!

## 🔌 API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/api/cabs` | 🚖 Get available cabs |
| POST | `/api/cabs` | 📌 Book a cab |
| GET | `/api/bookings/{id}` | 📜 Get booking details |

## 🤝 Contributing
Feel free to fork the repository and create a pull request with improvements.

## 📜 License
This project is licensed under the MIT License.

