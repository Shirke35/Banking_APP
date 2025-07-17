# 💰 Banking Account CRUD App

A simple Spring Boot CRUD application to manage banking accounts. Built to strengthen backend fundamentals using modern Java and REST practices.

---

## ⚙️ Tech Stack

- Java 17  
- Spring Boot  
- Spring Data JPA  
- MySQL  
- Lombok  
- Postman

---

## 🔁 How It Works

1. REST request sent via Postman  
2. Hits Controller → Service → Repository  
3. Data stored/retrieved from MySQL DB

---

## 🔧 Endpoints (Sample)

| Method | Endpoint              | Action            |
|--------|-----------------------|-------------------|
| GET    | `/api/accounts`       | Get all accounts  |
| GET    | `/api/accounts/{id}`  | Get by ID         |
| POST   | `/api/accounts`       | Create account    |
| PUT    | `/api/accounts/{id}`  | Update account    |
| DELETE | `/api/accounts/{id}`  | Delete account    |

---

## 🚀 Run Locally

```bash
git clone https://github.com/yourusername/banking-app.git
cd banking-app
./mvnw spring-boot:run

**Make sure MySQL is running and DB credentials are set in application.properties.**

👩‍💻 Author
Sanika Shirke
LinkedIn | GitHub
