
# 📚 Bookstore RESTful API

A RESTful API for a Bookstore application, managing books, authors, customers, carts, and orders using **JAX-RS (Jersey)**, **JSON**, and **in-memory storage**.

---

## ✨ Features

- 📘 CRUD operations for **Books**, **Authors**, and **Customers**
- 🛒 Manage **Carts** (add/remove books, update quantities)
- 📦 Create and view **Orders** from carts
- 🔄 JSON-based request/response bodies
- ⚠️ Custom error handling for invalid inputs and missing resources

---

## 🛠️ Technology Stack

- ☕ Java EE 8 Web with **JAX-RS (Jersey)** for RESTful services
- 🧾 JSON for data exchange
- 🧪 Postman for API testing
- 🧠 In-Memory Storage (**ArrayList**, **HashMap**) for data
- 🌐 Apache Tomcat 9 as the server
- 💻 Apache NetBeans as the IDE

---

## 🧰 Setup Instructions

### ✅ Prerequisites

- Java JDK 17 or higher (compatible with Java EE 8)
- Apache NetBeans IDE
- Apache Tomcat 9
- Postman for testing

---

### 📥 Clone the Repository

```bash
git clone https://github.com/your-username/bookstore-api.git
cd bookstore-api
```

---

### 💡 Open in Apache NetBeans

- Import the project as a Maven project in NetBeans
- Ensure **Tomcat 9** is configured as the server in NetBeans

---

### 🏗️ Build and Deploy

- Use NetBeans to build the project (**Clean and Build**)
- Deploy to **Apache Tomcat 9** via NetBeans (**Run** or **Deploy**)

The API will be accessible at:

```
http://localhost:8080/bookstore-api/api/
```

---

### 📬 Test with Postman

- Test all endpoints using predefined requests

---

## 🔗 API Endpoints

### 📘 Books (`/books`)
- `POST`, `GET`, `GET/{id}`, `PUT/{id}`, `DELETE/{id}`

### ✍️ Authors (`/authors`)
- `POST`, `GET`, `GET/{id}`, `PUT/{id}`, `DELETE/{id}`
- `GET/{id}/books`

### 👤 Customers (`/customers`)
- `POST`, `GET`, `GET/{id}`, `PUT/{id}`, `DELETE/{id}`

### 🛒 Carts (`/customers/{customerId}/cart`)
- `POST/items`, `GET`, `PUT/items/{bookId}`, `DELETE/items/{bookId}`

### 📦 Orders (`/customers/{customerId}/orders`)
- `POST`, `GET`, `GET/{orderId}`

---

## 🎥 Demo Video

📺 **Watch the API demonstration**: *https://youtu.be/MdulQHz6W18*  
The video shows Postman requests, HTTP methods, status codes, and error handling.

---

## 📄 License

📚 For **academic purposes only**, not for commercial use.
```
