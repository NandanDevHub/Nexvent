<p align="center">
  <img src="assets/nexvent_logo.svg" width="80" alt="Nexvent Logo" style="vertical-align:middle;margin-right:8px;">
</p>

# Nexvent

Nexvent is a full stack event management platform that allows users to create, join, and chat around real world activities in real time.  
It is built with React on the frontend and ASP.NET Core Web API on the backend, following clean architecture and production grade patterns.

## ✨ Features

- User authentication and profile management  
- Create, edit, and delete events  
- Join and manage attendance for events  
- Real-time chat using SignalR  
- Image upload and profile photo handling  
- Activity filtering, sorting, and pagination  
- Responsive UI built with Semantic UI  
- MobX state management  
- API built using CQRS + Mediator pattern  
- Secure authentication with JWT

## 🏗 Tech Stack

**Frontend**  
- React
- MobX  
- Semantic UI React  
- Axios  
- React Router  

**Backend**  
- ASP.NET Core Web API  
- Entity Framework Core  
- MediatR (CQRS Pattern)  
- Identity + JWT  
- SignalR


# 🚀 Getting Started

### Prerequisites
- Node.js
- .NET SDK

### Setup

1. Clone the repository
   git clone https://github.com/NandanDevhub/nexvent.git

2. Install frontend dependencies
   cd client
   npm install

3. Start the frontend
   npm start

4. Run the backend
   cd API
   dotnet run

5. Open your browser at
   http://localhost:3000

## 🛡 License

This project is licensed under the MIT License, see the [LICENSE](LICENSE.md) file for details.
