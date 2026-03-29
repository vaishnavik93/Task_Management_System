#🗂️ Task Management System

A full-stack Task Management Application built with **.NET 10 (Web API & MVC)** and **Angular (v17+)**.
Features a beautiful, responsive, glassmorphism-inspired UI and an Entity Framework In-Memory Database for rapid testing.

📌 Overview

This project demonstrates a complete full-stack workflow including task creation, retrieval, updating, and deletion.
It follows a layered backend architecture and uses Angular for a responsive frontend.

## 🚀Features
- **Frontend**: Angular standalone components, reactive forms, vibrant styling, animations. 
- **Backend**: Repository pattern, Service layer, EF Core In-Memory database, CORS enabled.
- **SSR**: There is a Server-Side Rendered (SSR) Razor view demonstrating task fetching directly from the backend services via MVC.

🛠 Tech Stack

Frontend
Angular (Standalone Components)
TypeScript
Reactive Forms
HTML, CSS (Modern UI)

Backend
.NET Web API
MVC (for SSR demo)
Entity Framework Core (In-Memory DB)
Repository Pattern
Service Layer Architecture

📁 Project Structure
Task-Management-System/
├── Frontend/   # Angular Application
├── Backend/    # .NET Web API + MVC

⚙️ Setup Instructions

1️⃣ Clone Repository
git clone https://github.com/vaishnavik93/Task_Management_System.git
cd Task_Management_System

2️⃣ Run Backend
cd Backend
dotnet run --urls="https://localhost:5001"

Backend runs on:
👉 https://localhost:5001

SSR View:
👉 https://localhost:5001/Home

3️⃣ Run Frontend
cd Frontend
npm install
ng serve

Frontend runs on:
👉 http://localhost:4200

### Troubleshooting
- **CORS Errors**: Ensure the backend is running on `https://localhost:5001`. If it's on a different port, update the `apiUrl` in `Frontend/src/app/services/task.service.ts` to match the backend URL.
- **Missing Modules**: If the frontend fails to compile, try running `npm install` again.

👨‍💻 Author
VAISHNAVI KESARWANI
