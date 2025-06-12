
# 📚 Book Management Fullstack App — React + Node.js + Docker

Hands-on fullstack project to apply and demonstrate key concepts in modern web development: React frontend, Node.js + Express backend, RESTful API, database migrations, and Dockerized deployment.

---

## 🚀 Tech Stack

| Layer      | Technology |
|------------|-------------|
| Frontend   | React (JavaScript) |
| Backend    | Node.js + Express |
| Database   | SQLite (via Knex.js ORM) |
| Deployment | Docker & Docker Compose |

---

## 📌 Features

- ✅ Fullstack React + Node.js Application
- ✅ RESTful API (CRUD for books)
- ✅ Database migrations and seed data (Knex.js)
- ✅ Frontend routing with React Router
- ✅ Axios-based API communication
- ✅ Dockerized backend for easy deployment
- ✅ Simple & clean folder structure for learning

---

## 🧱 Project Structure

### Frontend

```
src/
├── App.js
├── index.js
├── routes.js
├── global.css
├── services/
│   └── api.js
└── pages/
    ├── Books/
    │   ├── index.js
    │   └── styles.css
    └── NewBook/
        ├── index.js
        └── styles.css
```

### Backend

```
src/
├── controllers/
│   └── BookController.js
├── database/
│   ├── connection.js
│   └── migrations/
│       ├── 20201103201523_create_table_book.js
│       └── 20210110140502_insert_books.js
├── routes.js
└── index.js

Other files:
- Dockerfile
- startup.sh
- wait-for.sh
- knexfile.js
- package.json
```

---

## 🐳 Running the Backend with Docker

```bash
docker build -t book-api .
docker run -p 3333:3333 book-api
```

Or using Docker Compose (if configured).

---

## 🌐 Running the Frontend (React)

```bash
npm install
npm start
```

Frontend runs on: [http://localhost:3000](http://localhost:3000)  
Backend runs on: [http://localhost:3333](http://localhost:3333)

> ⚠️ Adjust Axios baseURL if needed inside `services/api.js`.

---

## 🎯 Learning Goals

- ✅ Fullstack integration between React and Node.js
- ✅ API development using Express
- ✅ Database schema migrations with Knex.js
- ✅ Docker containerization
- ✅ Axios and frontend/backend communication

---

## 📄 License

MIT License

---

## 👤 Author

**Guilherme Fabris**  
[GitHub](https://github.com/gfabrissouza)
