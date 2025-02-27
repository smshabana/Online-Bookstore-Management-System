# **📚 Online Bookstore Management System**  

## **Overview**  
The **Online Bookstore Management System** is a full-stack web application built with **Spring Boot** and **React.js**. It allows users to browse books, add them to their cart, and manage their purchases. The system includes **user authentication, book catalog management, a shopping cart, and an admin panel** for managing books.  

---

## **🛠 Tech Stack**  
- **Backend**: Spring Boot, Spring Data JPA, MySQL, Spring Security  
- **Frontend**: React.js, Axios, Bootstrap  
- **Database**: MySQL  
- **Tools**: Maven, Git, Postman  

---

## **🚀 Features**  
✅ **User Authentication & JWT Security** – Secure login and user management  
✅ **Book Catalog** – View, search, and filter books  
✅ **Shopping Cart** – Add books to cart and proceed to checkout  
✅ **Admin Dashboard** – Manage books (Add, Edit, Delete)  
✅ **REST API Integration** – Fetch and update data dynamically  

---

## **📂 Project Structure**  
```
/bookstore-backend  (Spring Boot Backend)
  ├── src/main/java/com/bookstore
  │   ├── controller/
  │   ├── model/
  │   ├── repository/
  │   ├── service/
  │   ├── BookstoreApplication.java
  ├── src/main/resources/application.properties
  ├── pom.xml

/bookstore-frontend  (React.js Frontend)
  ├── src/components/
  │   ├── BookList.js
  │   ├── AddBook.js
  │   ├── Cart.js
  ├── src/App.js
  ├── package.json
```

---

## **💻 Setup Instructions**  
### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/bookstore.git
cd bookstore
```

### **2️⃣ Setup Backend (Spring Boot)**  
```sh
cd bookstore-backend
mvn spring-boot:run
```
Backend runs on **http://localhost:8080** 🚀  

### **3️⃣ Setup Frontend (React.js)**  
```sh
cd bookstore-frontend
npm install
npm start
```
Frontend runs on **http://localhost:3000** 🎨  

---
## **📜 License**  
This project is **open-source** under the **MIT License**.  

---

🚀 Happy Coding! 😊

