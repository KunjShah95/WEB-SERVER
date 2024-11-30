
# My Own Web Server

![Status](https://img.shields.io/badge/status-active-brightgreen) 
![Language](https://img.shields.io/badge/language-Python-blue) 
![License](https://img.shields.io/badge/license-MIT-orange)

## 📖 Overview
**My Own Web Server** is a lightweight, Python-based HTTP server designed to serve static files like HTML and JSON. This project showcases fundamental server-client interactions and demonstrates efficient handling of HTTP requests and errors. It is a great starting point for anyone exploring the inner workings of web servers.



## 🌟 Features
- **Serve Static Files**: Handles requests for HTML and JSON files efficiently.
- **Custom Error Handling**: Provides user-friendly responses for common errors such as:
  - `404 Not Found`
  - `405 Method Not Allowed`
- **Dynamic File Serving**:
  - Serves `index.html` for the root path (`/`).
  - Serves `book.json` when the `/book` endpoint is accessed.
- **Minimalistic and Educational**: Simple architecture suitable for learning and extension.


## 🛠 Prerequisites
- Python 3.6 or higher
- Basic understanding of HTTP and networking concepts
- File system containing:
  - `index.html`: HTML file representing the homepage.
  - `book.json`: A JSON file containing sample book details.


## 🚀 Getting Started

### Clone the Repository
To get started, clone this repository to your local system:

git clone https://github.com/KunjShah95/my-own-web-server.git
cd my-own-web-server

### Run the Server
Follow these steps to launch the server:
1. Verify the presence of `main.py`, `index.html`, and `book.json` in the project directory.
2. Execute the Python server script:
   
   python main.py
   
3. Open your web browser and visit `http://localhost:8080`.



## 📂 Directory Structure
The project files are organized as follows:

├── book.json       
 # Sample JSON file containing book details
├── index.html      
 # Static HTML file serving as the homepage
├── main.py         
 # Python script implementing the web server




## ⚙️ How It Works
1. **Server Initialization**:
   - The server listens for incoming connections on `0.0.0.0` at port `8080`.
2. **Request Handling**:
   - **Root Path (`/`)**: Serves the `index.html` file as the homepage.
   - **Book Path (`/book`)**: Serves the `book.json` file with `application/json` content type.
   - **Other Paths**: Returns a `404 Not Found` response.
   - **Unsupported HTTP Methods**: Returns a `405 Method Not Allowed` response.
3. **Error Management**:
   - Ensures graceful handling of invalid requests and provides meaningful error messages.



## 🛠 Technologies Used
- **Python**: Core programming language for the server implementation.
- **Socket Programming**: Handles server-client communication.
- **HTTP Protocol**: Serves static files and processes HTTP requests.


## 🤝 Contributing
Contributions are always welcome! To contribute:
1. Fork the repository.
2. Create a new branch:

   git checkout -b feature/your-feature
   
4. Commit your changes:
   
   git commit -m "Add your message"
   
5. Push to the branch:
   
   git push origin feature/your-feature
   
6. Open a pull request.



## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for detailed terms and conditions.


## 📚 Acknowledgments
This project is inspired by the simplicity of learning projects. Special thanks to the open-source community for their valuable resources and guidance.


