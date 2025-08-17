
---

# 🗨️ C++ Console Chat App

A simple **console-based chat application** built in **C++** that demonstrates how to implement a server–client architecture using **WebSockets**. This project is great for learning **network programming, sockets, and inter-process communication**.

---

## 🚀 Features

* Console-based client and server written in **C++**
* **WebSocket-based communication** for real-time messaging
* Multiple clients can connect to the same server
* Real-time **two-way communication** between clients
* Lightweight and easy to run locally

---

## 📂 Project Structure

```
.
├── server.cpp   # WebSocket server implementation
├── client1.cpp  # First chat client
├── client2.cpp  # Second chat client
└── README.md    # Documentation
```

---

## 📘 What You’ll Learn

By exploring this project, you’ll gain hands-on experience with:

* 🖥️ **Server–client architecture** in C++
* 🔌 **WebSockets** for real-time communication
* 📡 **Networking basics** (connections, messages, sockets)
* 🛠️ Compiling and running C++ programs with multiple executables
* 👨‍💻 Building a foundation for **scalable chat systems** (extendable to multiple clients)

This project is a **great starting point** for anyone interested in **network programming, distributed systems, or backend engineering**.

---

## ⚡ How It Works

1. Start the **server**:

   ```bash
   ./server
   ```

   The server starts listening for client connections.

2. Run **client1**:

   ```bash
   ./client1
   ```

   `client1` connects to the server.

3. Run **client2**:

   ```bash
   ./client2
   ```

   `client2` also connects to the server.

4. Now, **client1** and **client2** can chat with each other through the server.

---

## 🛠️ Requirements

* **C++11** or higher
* A C++ compiler (`g++`, `clang++`, etc.)
* WebSocket library (depending on your implementation, e.g., [Boost.Asio](https://www.boost.org/doc/libs/release/doc/html/boost_asio.html), `libwebsocketpp`, or similar)

---

## 🔧 Build Instructions

Compile the files using **g++** (or another compiler):

```bash
g++ server.cpp -o server
g++ client1.cpp -o client1
g++ client2.cpp -o client2
```

---

## 📌 Usage Example

```bash
# Run the server
./server

# In another terminal, run client1
./client1

# In another terminal, run client2
./client2
```

✅ Clients are now connected and can exchange messages in real time.

---

## 🌟 Future Improvements

* Support for more than two clients
* Private messaging between clients
* Group chat rooms
* Cross-network communication (not just localhost)
* GUI version of the chat app

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---
