🏃 Run Tracker – Spring Boot App
A simple Spring Boot application that allows users to log their running activities and fetch past runs. Designed as a minimal REST API for learning backend development, CRUD operations, and working with databases using Java Spring Boot.

📋 Features
➕ Add a new run with details like distance, duration, and date

📄 View all runs submitted by a user

🔍 Fetch specific runs by ID

🗑️ Delete a run

🛠️ Built with clean code practices and RESTful architecture

⚙️ Tech Stack
Java 17

Spring Boot 3

Spring Data JPA

H2 (In-memory database) or PostgreSQL/MySQL if configured


Maven

🧪 Endpoints Overview
Method	Endpoint	Description
POST	/api/runs	Create a new run entry
GET	/api/runs	Get all run entries
GET	/api/runs/{id}	Get a specific run by ID
DELETE	/api/runs/{id}	Delete a run by ID

📌 Future Enhancements
 Update run details (PUT)

 Add user authentication

 Connect to a persistent PostgreSQL database

 Add frontend or expose the API to a mobile app
