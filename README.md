# Event Manager

Event Manager is a Node.js backend application for managing users and events.
It demonstrates backend development concepts such as server setup, database modeling, and ORM usage with SQLite.

---

## Features

- User creation and retrieval
- Admin user auto-creation on server start
- Event creation and listing
- SQLite database with Sequelize ORM
- Automatic database and table initialization
- Server auto-restart during development using Nodemon
- EJS templating for rendering views

---

## Tech Stack

- Node.js
- Express.js
- Sequelize (ORM)
- SQLite
- EJS
- Nodemon

---

## Project Structure

```
Event Manager/
├── index.js
├── package.json
├── package-lock.json
├── views/
│   └── viewUsers.ejs
├── models/
├── routes/
├── config/
├── controllers/
```

---

## Setup & Usage

### 1. Clone the repository
```
git clone https://github.com/YOUR_USERNAME/event-manager.git
cd event-manager
```

### 2. Install dependencies
```
npm install
```

### 3. Start the server
```
npm start
```

Server runs at:
```
http://localhost:3000
```

---

## Database

- Uses SQLite for simplicity
- Tables are automatically created on server startup
- An admin user is auto-created if one does not exist
- Database files are excluded from version control

---

## Example Console Output

```
Server is running on port http://localhost:3000
Database & tables created!
Admin already exists.
```

---

## Future Improvements

- User authentication (JWT)
- Role-based access control
- REST API documentation
- Frontend UI improvements
- Cloud deployment

---

## Author

**Mosh1132**
