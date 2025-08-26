
# Perfume Webstore – E-commerce Platform

<div align="center">

[![Build Status](https://travis-ci.com/merikbest/ecommerce-spring-reactjs.svg?branch=travis-ci-test)](https://travis-ci.com/merikbest/ecommerce-spring-reactjs)
[![codecov](https://codecov.io/gh/merikbest/ecommerce-spring-reactjs/branch/travis-ci-test/graph/badge.svg?token=sEfOfpBHDX)](https://codecov.io/gh/merikbest/ecommerce-spring-reactjs)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=200&section=header&text=Perfume%20Webstore&fontSize=45&fontColor=fff&animation=fadeIn&fontAlign=50&desc=Spring%20Boot%20+%20React%20+%20PostgreSQL&descSize=18&descAlign=50&descAlignY=75" />

[![Java](https://img.shields.io/badge/Java-8+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](#)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](#)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](#)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](#)
[![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)](#)
[![AWS](https://img.shields.io/badge/AWS_S3-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](#)
[![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

</div>

---

## 📌 **Overview**
The **Perfume Webstore** is a full-featured **E-commerce platform** built with **Spring Boot, PostgreSQL, and React.js**.  
It supports **authentication (JWT & OAuth2)**, **product management**, **shopping cart functionality**, **order management**, and **payment-ready workflows**.

**Live Demo:** http://perfume-web.tk  
**Admin Login:** `admin@gmail.com` / `admin`

---

## **Key Features**
- **User Authentication:**  
  - Secure login with **JWT** & email verification  
  - Social login with **Google, Facebook, Github**
- **Product Management:**  
  - Search & filter products by criteria  
  - Add, edit, or remove products (Admin only)
- **Shopping Experience:**  
  - Cart operations with real-time updates  
  - Place and track orders
- **User Account Management:**  
  - Update profile & change password  
  - View order history
- **Admin Features:**  
  - Manage users & their orders  
  - Full CRUD operations on products

---

## **Tech Stack**

### **Backend**
- Java 8+, Spring Boot, Spring Data JPA, Spring Security (JWT/OAuth2)
- PostgreSQL
- JUnit, Mockito

### **Frontend**
- React.js (TypeScript), Redux Toolkit
- Ant Design UI
- Jest for unit testing

### **Other**
- REST API + GraphQL
- AWS S3 (File Storage), Heroku (Backend Deployment)
- reCAPTCHA, Gmail SMTP
- Build Tools: Maven, npm, yarn, webpack

---

## **Installation Guide**

### **Prerequisites**
- Java 8+
- Maven
- PostgreSQL (with databases `perfume` & `perfumetest`)
- Node.js & npm
- AWS S3 account (for media storage)
- Gmail account (SMTP)
- OAuth2 credentials (Google)

### **Setup**

1. **Backend**
   - Configure `application.properties`:
     - PostgreSQL credentials
     - AWS S3 keys
     - Gmail SMTP credentials
     - OAuth2 credentials
   - Run the application:
     ```bash
     mvn spring-boot:run
     ```
   - API available at: `http://localhost:8080`

2. **Frontend**
   ```bash
   cd frontend
   npm install
   npm start
   ```
   - App available at: `http://localhost:3000`

3. **Swagger Documentation**
   - Local: `http://localhost:8080/swagger-ui.html`
   - Live: `https://perfume-websore-api.herokuapp.com/swagger-ui.html`

---

## **Screenshots**

Menu | Product
:---:|:---:
![Menu](https://i.ibb.co/VT4RzYj/1menu.jpg) | ![Product](https://i.ibb.co/HtnKp0W/2-Product-page.jpg)

Cart | Order
:---:|:---:
![Cart](https://i.ibb.co/8Y8bfSG/3-Cart.jpg) | ![Order](https://i.ibb.co/tLmY8y2/4-Ordering.jpg)

Profile | Admin Panel
:---:|:---:
![Profile](https://i.ibb.co/qx1Csc8/7-User-profile-page.jpg) | ![Admin](https://i.ibb.co/jH8R8xL/10-Edit-perfume-page.jpg)

---

## **About the Maintainer**

### **Deekshitha Obulreddygari – Java Full Stack Developer**
- **Email:** [obulreddygarideekshitha@gmail.com](mailto:obulreddygarideekshitha@gmail.com)  
- **LinkedIn:** [linkedin.com/in/deekshitha-obulreddygari](https://linkedin.com/in/deekshitha-obulreddygari)  
- **Location:** Phoenix, AZ  

> *"Building robust, scalable solutions with modern full-stack technologies."*

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=100&section=footer"/>
</div>
