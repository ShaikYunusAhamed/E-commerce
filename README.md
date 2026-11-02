# 🛒✨ E-Commerce Spring Boot Project  
### A modern shopping application with Cart System & PDF Receipt Generation

![Java](https://img.shields.io/badge/Java-17-red)
![Spring Boot](https://img.shields.io/badge/SpringBoot-3.3.4-green)
![MySQL](https://img.shields.io/badge/Database-MySQL-blue)
![Thymeleaf](https://img.shields.io/badge/UI-Thymeleaf-yellow)
![Gradle](https://img.shields.io/badge/Build-Gradle-white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🚀 Project Overview

A complete **E-Commerce Web Application** built using **Spring Boot + Thymeleaf + MySQL**.

This project allows users to:

- Browse products  
- Add to cart  
- Increase / decrease quantity  
- Remove items  
- Download PDF receipt for cart  
- Buy a single product with a PDF bill  
- Login & Signup  
- Personalized greeting (“Welcome, username”)

---

## 🎯 Features

### 🔐 User Authentication
- Login / Signup  
- Session-based authentication  
- Navbar displays logged-in username  

### 🛍 Product Features
- Product list with images, name, price  
- Smooth UI animations  
- Add to Cart  
- Buy Now button for single-item purchase  

### 🛒 Cart System
- View cart  
- Increase quantity  
- Decrease quantity  
- Remove product  
- Auto-calculated total  
- PDF receipt generation  

### 📄 PDF Receipt (Using OpenPDF)
Includes:
- Username  
- Date & time  
- Items purchased  
- Price × quantity  
- Grand total  

### 🎨 UI / UX
- Modern glassmorphism design  
- Gradient colors  
- Clean product cards  
- Fully responsive layout  

---

## 🏗 Tech Stack

**Backend**
- Java 17  
- Spring Boot 3.3  
- Spring MVC  
- Spring Data JPA  
- Hibernate  

**Frontend**
- Thymeleaf  
- HTML, CSS  

**Database**
- MySQL  

**Build Tool**
- Gradle  

## ⚙️ How to Run the Project

### 1️⃣ Clone the repository
git clone https://github.com/Arjun1266/ecommerce-springboot-project.git

cd ecommerce-springboot-project

### 2️⃣ Create MySQL database
CREATE DATABASE ecom1;


### 3️⃣ Configure database in application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecom1
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true


### 4️⃣ Run the project
./gradlew bootRun


### 5️⃣ Visit in browser  
http://localhost:8080

---

## 📁 Folder Structure

src/
├── main/
│ ├── java/com/example/demo/
│ │ ├── controller/
│ │ ├── entity/
│ │ ├── repo/
│ │ ├── service/
│ ├── resources/
│ │ ├── templates/
│ │ ├── static/
