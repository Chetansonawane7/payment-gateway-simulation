# 💳 Payment Gateway Simulation

A backend application built using **Java**, **Spring Boot**, and **PostgreSQL** that simulates a real-time payment gateway system.

---

## 🚀 Features

- ✅ Create a new payment request
- 🔁 Update payment status (`INITIATED`, `SUCCESS`, `FAILED`)
- 🔍 Retrieve payment details by ID
- 📋 View all transactions
- 🌐 RESTful APIs tested with Postman

---

## 🛠 Tech Stack

| Layer         | Technology             |
|---------------|------------------------|
| Backend       | Java 17, Spring Boot   |
| Database      | PostgreSQL             |
| ORM           | JPA / Hibernate        |
| API Testing   | Postman                |
| Build Tool    | Maven                  |

---

## 📦 API Endpoints

| Method | Endpoint                  | Description                |
|--------|---------------------------|----------------------------|
| `POST` | `/api/payments`           | Create new payment         |
| `GET`  | `/api/payments/{id}`      | Get payment by ID          |
| `PUT`  | `/api/payments/{id}/status?status=SUCCESS` | Update payment status |
| `GET`  | `/api/payments`           | List all payments          |

---

## 🧪 Sample JSON Payload

### ➕ Create Payment
```json
{
  "payerName": "Chetan",
  "amount": 500.0
}
```

🧰 How to Run
1. Clone the repo:
```bash
git clone https://github.com/your-username/payment-gateway-simulation.git
cd payment-gateway-simulation
```

2. Configure application.properties with your PostgreSQL DB.

3. Run the Spring Boot app:
```bash
mvn spring-boot:run
```

4. Open Postman and test endpoints at:
```bash
http://localhost:8080/api/payments
```

🙋‍♂️ Author
Chetan Sonawane
🔗 https://www.linkedin.com/in/chetan-sonawane-449a1a242/
📫 sonawanechetan847@gmail.com

