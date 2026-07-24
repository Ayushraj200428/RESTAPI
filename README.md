# REST API

A simple RESTful API built with **Node.js** and **Express.js** that serves user data in JSON format.

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Ayushraj200428/RESTAPI.git
   cd RESTAPI
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the server
   ```bash
   npm start
   ```

The server will start at **http://localhost:8000**

---

## 📡 API Endpoints

### Users

| Method   | Endpoint          | Description              |
|----------|-------------------|--------------------------|
| `GET`    | `/api/users`      | Get all users            |
| `GET`    | `/api/users/:id`  | Get a single user by ID  |
| `POST`   | `/api/users`      | Create a new user        |
| `PATCH`  | `/api/users/:id`  | Update a user by ID      |
| `DELETE` | `/api/users/:id`  | Delete a user by ID      |

---

## 📋 Example Requests

### Get all users
```
GET http://localhost:8000/api/users
```

### Get user by ID
```
GET http://localhost:8000/api/users/1
```

### Create a new user
```
POST http://localhost:8000/api/users
```

### Update a user
```
PATCH http://localhost:8000/api/users/1
```

### Delete a user
```
DELETE http://localhost:8000/api/users/1
```

---

## 🛠️ Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js v5
- **Data:** JSON (MOCK_DATA.json)

## 📁 Project Structure

```
REST API/
├── index.js          # Main server file
├── MOCK_DATA.json    # Mock user data
├── package.json      # Project metadata & dependencies
└── .gitignore        # Files ignored by git
```
