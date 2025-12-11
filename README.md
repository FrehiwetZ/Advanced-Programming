# 📩 Real-Time Chat Application

This is a real-time chat application built with **Spring Boot**, **WebSocket (STOMP)**, **SockJS**, and a simple **HTML/JavaScript** frontend.  
It allows users to connect, enter their name, send messages, and see chat updates instantly without refreshing the page.

--- 

## 🚀 Features

- Real-time messaging using WebSocket + STOMP  
- Multiple users can chat at the same time  
- Simple and clean UI built with Bootstrap  
- Automatic scrolling to the latest message  
- JSON-based message structure (`sender`, `content`)  

---

## 🛠️ Technologies Used

### **Backend**
- Java 17+
- Spring Boot (WebSocket)
- STOMP protocol
- SockJS fallback support

### **Frontend**
- HTML5
- Bootstrap 5
- JavaScript (Stomp.js + SockJS)

---

## 📡 How It Works

1. User opens the chat page.  
2. The frontend connects to the WebSocket endpoint:
3. User types a message → it is sent to:
4. The backend receives it, then broadcasts to all users through:
5. All connected clients display the new message instantly.  

---

## ▶️ How to Run the Project

**1. Clone the repository**
## 🔗 GitHub Repository 
git clone https://github.com/FrehiwetZ/Advanced-Programming.git 
***2. Open the project in IntelliJ**
IntelliJ will automatically download the dependencies (Maven or Gradle).
***3. Run the Spring Boot Application**
Open the main class (with @SpringBootApplication)
Click the green Run button
***4. Open the chat UI**
Go to: http://localhost:8080/
Open this page in multiple tabs to test real-time messaging.

Project Structure
src/main/java/...   → Spring Boot backend
src/main/resources/ → HTML, JS, templates

Author

Your Frehiwet Zerihun
Beginner Java + Spring Boot developer
This is my first real-time chat application project.


---




  

