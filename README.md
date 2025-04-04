# Smart Contact Manager

A full-stack Contact Manager application that lets you add, edit, and delete contacts. The project uses **React, JavaScript, and Tailwind CSS** on the frontend and **Spring Boot, MySQL, JPA, Hibernate** on the backend. Communication between the frontend and backend is handled via **Axios**, while **React Motion** provides smooth animations and **React Router** manages client-side routing.

## Features

- **CRUD Operations:** Create, read, update, and delete contacts.
- **HTTP Client (Axios):** Utilized Axios, a promise-based HTTP client, to perform asynchronous API calls between the React frontend and the Spring Boot backend.
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Smooth Animations:** Implemented with React Motion.
- **Routing:** Handled by React Router for a seamless navigation experience.
- **Backend API:** Powered by Spring Boot and JPA (Hibernate) for efficient data management.
- **Data Persistence:** Contacts stored in a MySQL database.

---

## Tech Stack

### Frontend

- **React** with JavaScript
- **Tailwind CSS** for styling
- **React Motion** for animations
- **React Router** for navigation
- **Axios** for API calls

### Backend

- **Spring Boot**
- **MySQL**
- **JPA** (Hibernate)
- **Maven** for project management

---

## Screenshots

### Homepage
![Homepage](https://github.com/user-attachments/assets/0cfcb826-918b-4f18-9a02-848852cf1de9)

### Contact Adding Page
![Add Contact](https://github.com/user-attachments/assets/578f2c11-df0c-459b-b431-b14b50b36d91)

### Mobile Responsive View
![Mobile View](https://github.com/user-attachments/assets/84590fa8-4628-4c95-9924-1dea3571cf1d)

---

## Installation & Setup

### Prerequisites

- **Java 19**
- **Maven 3.6+**
- **Node.js and npm**
- **MySQL8**

### Backend Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Aarav-Mahto/ContactManager.git
   cd contact-manager
   cd SpringBoot-backend

2. **MySQL Database Configuration (application.yml)**
```sh
spring:
  application:
    name: smartApi
    
  datasource:
    driver-class-name: com.mysql.cj.jdbc.Driver
    url: jdbc:mysql://localhost/contact_api?allowPublicKeyRetrieval=true&useSSL=false&serverTimezone=UTC
    username: *****
    password: *****

#CREATE DATABASE contact_api; - to create mysql database
```  
3. **Run Spring Boot Backend:**   
  ```sh
  mvn clean install
  mvn spring-boot:run
```
### **Now Locate to /react-frontend:**
   ```sh
   npm install
   npm run dev
   ```
## Use This Url to access application 
REACT_APP_API_BASE_URL= `https://localhost:_port_/contacts`

Thanks
