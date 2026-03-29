# Task Management System

A full-stack Task Management Application built with **.NET 6 (Web API & MVC)** and **Angular (v17+)**.
Features a beautiful, responsive, glassmorphism-inspired UI and an Entity Framework In-Memory Database for rapid testing.

## Features
- **Frontend**: Angular standalone components, reactive forms, vibrant styling, animations. 
- **Backend**: Repository pattern, Service layer, EF Core In-Memory database, CORS enabled.
- **SSR**: There is a Server-Side Rendered (SSR) Razor view demonstrating task fetching directly from the backend services via MVC.

## Prerequisites
- .NET 6 SDK (or a compatible newer SDK)
- Node.js & npm
- Angular CLI (`npm install -g @angular/cli`)

## Getting Started

### 1. Run the Backend API
```powershell
cd Backend
dotnet run --urls="https://localhost:5001"
```
The API will be available at `https://localhost:5001/api/tasks`.
*Note: To view the Server-Side Rendered (SSR) Razor View, navigate to `https://localhost:5001/Home` in your browser.*

### 2. Run the Angular Frontend
```powershell
cd Frontend
npm install
ng serve -o
```
The application will open in your browser at `http://localhost:4200`.

### Troubleshooting
- **CORS Errors**: Ensure the backend is running on `https://localhost:5001`. If it's on a different port, update the `apiUrl` in `Frontend/src/app/services/task.service.ts` to match the backend URL.
- **Missing Modules**: If the frontend fails to compile, try running `npm install` again.
