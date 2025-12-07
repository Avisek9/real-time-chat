# Real-Time Chat Application

A real-time chat application built using Spring Boot, Thymeleaf, and WebSocket with STOMP protocol, enabling live messaging between multiple users with a server-rendered UI and real-time updates.

This project demonstrates real-time communication, event-driven messaging, and WebSocket-based application design.

---

## Features

- Real-time messaging using WebSocket and STOMP protocol  
- Multi-user chat support  
- Server-rendered frontend using Thymeleaf  
- Fully functional backend built with Spring Boot  
- Real-time message broadcasting  
- Easy to extend for private chat rooms and user authentication  
- Clean separation of backend messaging logic and frontend UI  

---

## Technology Stack

### Backend
- Java 21  
- Spring Boot  
- WebSocket  
- STOMP Protocol  
- Maven  

### Frontend
- Thymeleaf (Server-Side Rendered Templates)  

### Tools and Version Control
- Git  
- GitHub  

---

## Setup Instructions

Follow the steps below to run this project locally.

### Prerequisites

Make sure you have the following installed:

- Java 21  
- Maven  
- Git  

---

### Backend and Application Setup

git clone https://github.com/Avisek9/real-time-chat.git
cd your-project-folder  
mvn clean install  
mvn spring-boot:run  

The application will start on:

http://localhost:8080  

---

## How It Works

- Uses WebSocket for full-duplex communication between client and server  
- STOMP protocol is used for message routing and subscription handling  
- Thymeleaf renders the UI on the server  
- Messages are broadcast instantly to all connected users  

---

## Future Enhancements

- Private chat rooms  
- User authentication and authorization  
- Message persistence using database  
- Online/offline user status  
- Delivery and read receipts  

---

## Author

Abhishek Sahu

If you find this project useful, feel free to give it a star.

