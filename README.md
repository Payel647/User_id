# User CRUD Application

A simple **User Management CRUD App** built with **Node.js**, **Express.js**, and **SQL** database.
It uses **Faker.js** to generate random user data for testing purposes.

---

##  Features

*  Create a new user
*  View all users
*  Update existing user details
*  Delete a user
*  Dummy data generation using Faker.js

---

## 🛠️ Tech Stack

| Technology                            | Purpose                                  |
| ------------------------------------- | ---------------------------------------- |
| **Node.js**                           | Backend runtime environment              |
| **Express.js**                        | Web framework for routing and middleware |
| **SQL (MySQL)** | Database for user storage                |
| **Faker.js**                          | Random fake user data generation         |

---

## ⚙️ Setup Instructions

1. **Clone this repository**

   ```bash
   git clone https://github.com/Payel647/User_id.git
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

4. **Run the app**

   ```bash
   npm start
   ```

5. **Generate fake users (optional)**

   ```bash
   npm run seed
   ```

---

## 📡 API Endpoints

| Method   | Endpoint     | Description             |
| -------- | ------------ | ----------------------- |
| `GET`    | `/users`     | Get all users           |
| `GET`    | `/users/:id` | Get a single user by ID |
| `POST`   | `/users`     | Add a new user          |
| `PUT`    | `/users/:id` | Update a user           |
| `DELETE` | `/users/:id` | Delete a user           |

---

##  Example Dummy Data (via Faker.js)

```json
{
  "id": 1,
  "name": "John Doe",
  "email": "johndoe@example.com",
}
