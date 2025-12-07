# Real-Time Chat Application

A real-time chat application built using Spring Boot, Spring WebSocket, STOMP protocol, and Thymeleaf that enables instant messaging between multiple users through a server-rendered UI with real-time updates.

This project demonstrates event-driven communication, WebSocket-based messaging, and real-time client-server interaction.

---

## Features

- Real-time bi-directional messaging using WebSocket and STOMP protocol  
- Multi-user chat support  
- Server-rendered frontend using Thymeleaf  
- Real-time message broadcasting  
- Lightweight and scalable backend architecture  
- Clean separation of messaging logic and UI rendering  

---

## Technology Stack

### Backend
- Spring Boot  
- Spring WebSocket  
- Spring Messaging (STOMP Protocol)  
- Thymeleaf  
- Maven  

### Frontend
- Thymeleaf  
- JavaScript (ES6)  
- SockJS  
- STOMP.js  
- HTML  
- CSS  

---

## Setup Instructions

Follow the steps below to run this project locally.

### Prerequisites

- Java  
- Maven  
- Git  

---

### Application Setup

git clone https://github.com/Avisek9/real-time-chat.git

cd real-time-chat

mvn clean install

mvn spring-boot:run  

The application will start on:

http://localhost:8080  

---

## How It Works

- Client connects to the server using SockJS  
- STOMP protocol is used for message publishing and subscription  
- Spring WebSocket handles real-time bi-directional communication  
- Thymeleaf renders chat UI on the server  
- Messages are instantly broadcast to all connected users  

---

## Future Enhancements

- User authentication and authorization  
- Message persistence using database  
- Online/offline user status  
- Read receipts and delivery status  

---

## Author

Abhishek Sahu  
---

If you find this project useful, feel free to give it a star.
