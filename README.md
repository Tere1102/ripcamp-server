# Ingeina

Ingeina is a collaborative **Single Page Application** built with React, designed to connect current **web and data bootcamp students with alumni**.

The platform promotes **networking, mentorship, and community building** within the tech ecosystem.

This project was developed as a **team project during a web development bootcamp**, following agile methodologies and real-world collaboration practices.

---

## Technologies Used

### Frontend
- React
- React Router
- Axios
- Bootstrap
- HTML5
- CSS3

### Backend (Mock API)
- Node.js
- json-server
- CORS
- Morgan
- dotenv

---

## Mock Backend API – json-server

This project uses **json-server with custom middleware (CORS, Morgan)** to provide a **fake REST API** for frontend development.

The API is based on a local `db.json` file and simulates a real backend.

---

## API Endpoints

### 📌 Requests

| Method | Endpoint        | Description                          |
|--------|-----------------|--------------------------------------|
| GET    | /requests       | Get all requests                     |
| GET    | /requests/:id   | Get a request by ID                  |
| POST   | /requests       | Create a new request                 |
| PUT    | /requests/:id   | Update an existing request by ID     |
| DELETE | /requests/:id   | Delete a request by ID               |

---

### 🎓 Alumni

| Method | Endpoint              | Description           |
|--------|-----------------------|-----------------------|
| GET    | /alumni               | Get all alumni        |
| GET    | /alumni/:alumniId     | Get an alumni by ID   |

---

## Team Members

### Patricia Lago Espino
- GitHub: https://github.com/patriiilago  
- LinkedIn: https://www.linkedin.com/in/patri-lago

### Teresa Arranz Carrasco
- GitHub: https://github.com/Tere1102  
- LinkedIn: https://www.linkedin.com/in/teresa-arranz-carrasco

---

## Deployment

### Client
https://ingeina.netlify.app/

### Server
https://ingeina-server.fly.dev