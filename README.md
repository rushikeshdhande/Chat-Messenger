# Java Socket Programming – Client Server Chat Application

This project is a simple **Client-Server Chat Application** developed using **Java Socket Programming**.  
It allows a client and a server to communicate with each other by sending text messages continuously until the client types `end`.

---

## 📌 Features
- Two-way communication between client and server
- Uses TCP sockets
- Runs on localhost
- Simple console-based chat
- Terminates when client enters `end`

---

## 🛠️ Technologies Used
- Java
- Socket Programming
- TCP/IP
- Input/Output Streams

---

## 📂 Project Files
- `ChatServerLoop.java` – Server-side program
- `ChatClientLoop.java` – Client-side program

---

## ⚙️ How It Works
1. Server starts and listens on port **5100**
2. Client connects to the server using localhost and port **5100**
3. Client sends a message
4. Server receives the message and replies
5. This loop continues until client types `end`

---

## ▶️ How to Run the Program

### Step 1: Compile both files
```bash
javac ChatServerLoop.java
javac ChatClientLoop.java
