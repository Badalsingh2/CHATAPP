# ChatApp

A real-time chat application built using **Java** and **WebSocket**. This project demonstrates how to create a WebSocket-based chat system with modular Java code, allowing multiple clients to exchange messages in real time.

---

## 🚀 Features
- **Real-Time Communication**: Supports instant messaging using WebSocket.
- **Lightweight Design**: Built with a modular structure for scalability and clarity.
- **Maven Build**: Dependency and build management using Maven.
- **Customizable Configuration**: Easily configurable WebSocket endpoints.

---

## 📂 Project Structure

```plaintext
src/
├── main/
│   ├── java/com/chatapp/
│   │   ├── config/           # Configuration classes for WebSocket and application settings
│   │   ├── controllers/      # WebSocket controllers handling message communication
│   │   ├── models/           # Data models (e.g., Message)
│   │   └── ChatappApplication.java  # Main application entry point
│   └── resources/            # Application resources (e.g., application.properties)
├── test/                     # Unit tests for the application
```

---

## 🛠 Requirements
Before running the application, ensure you have the following installed:
- **Java 17+**
- **Maven 3.8+**
- A WebSocket testing tool (e.g., Postman, WebSocket Echo Test)

---

## 📦 Dependencies
This project uses the following dependencies:
- **Spring Boot**: Simplifies application setup and configuration.
- **Spring WebSocket**: Provides WebSocket support for Java-based applications.

All dependencies are managed through Maven (`pom.xml`).

---

## ⚙️ Setup and Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/chatapp.git
cd chatapp
```

### 2️⃣ Build the Project
Use Maven to build the project:
```bash
mvn clean install
```

### 3️⃣ Run the Application
Start the Spring Boot application:
```bash
mvn spring-boot:run
```

### 4️⃣ Connect a WebSocket Client
- Use a WebSocket testing tool or a custom client.
- Connect to the WebSocket server at:  
  `ws://localhost:8080/chat`
- Example JSON message format:
  ```json
  {
    "sender": "User1",
    "content": "Hello, world!"
  }
  ```

---

## 🧪 Testing
You can write and run unit tests for your controllers and models by placing test files in the `src/test/java` directory. Use:
```bash
mvn test
```

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing
Contributions are welcome! If you'd like to improve the app or fix a bug:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/my-feature`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature/my-feature`).
5. Open a pull request.

---

## 📧 Contact
For any questions or feedback, feel free to contact:
- **Name**: Badal Singh  
- **Email**: badalubentu@gmai..com  
- **GitHub**: [Badalsingh2](https://github.com/your-username)

---

Enjoy using **ChatApp**! 😊
