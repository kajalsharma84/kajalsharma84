# 🛍️ Shopverse – E-Commerce Backend API

**Shopverse** is a Spring Boot-based RESTful backend service that powers an online shopping platform.  
It manages product listings, order placement, customer data, and more with clean architecture and layered design.

---

## 🚀 Features

- ✅ Add / update / delete products
- 🛒 Place and track orders
- 👥 Handle customer records
- 📦 Inventory management-ready structure
- 🧱 Clean controller–service–repository architecture
- 💬 Global exception handling
- 🧪 Unit testing support

---

## 🛠️ Tech Stack

| Layer | Tools Used |
|-------|------------|
| Language | Java 17 |
| Framework | Spring Boot, Spring Web, Spring Data JPA |
| Database | MySQL / H2 |
| Build Tool | Maven |
| Testing | JUnit 5, Mockito |
| API Testing | Postman |
| Dev Tools | IntelliJ, VS Code |

---

## 📁 Project Structure

shopverse/
├── controller/
├── service/
├── repository/
├── model/
├── dto/
├── exception/
└── ShopverseApplication.java


---

## 📦 Getting Started

### 🔧 Prerequisites
- Java 17
- Maven
- MySQL (optional: use H2 for quick testing)

### ▶️ Run Locally

```bash
git clone https://github.com/kajalsharma84/shopverse.git
cd shopverse
./mvnw spring-boot:run


🔗 Sample API Endpoints

| Method   | Endpoint         | Description        |
| -------- | ---------------- | ------------------ |
| `GET`    | `/products`      | List all products  |
| `POST`   | `/products`      | Add a new product  |
| `DELETE` | `/products/{id}` | Delete a product   |
| `POST`   | `/orders`        | Place a new order  |
| `GET`    | `/orders/{id}`   | View order details |

🧪 Testing
./mvnw test


