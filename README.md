# Node.js Demo App

A simple Node.js application demonstrating basic Express.js server functionality. This app is designed as a beginner-friendly introduction to Node.js, Express, and Docker.

## 🚀 Features

- Lightweight Express server
- Basic routing
- JSON response
- Dockerized for easy deployment

## 🛠️ Tech Stack

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Docker](https://www.docker.com/)

## 📦 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (if running without Docker)
- [Docker](https://www.docker.com/)

### Clone the Repository

```bash
git clone https://github.com/Pallavipanjla/nodejs-demo-app.git
cd nodejs-demo-app
```

---

## 🚀 Run Locally (Without Docker)

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the server:

   ```bash
   node app.js
   ```

3. Visit `http://localhost:3000/` in your browser or API client.

---

## 🐳 Run with Docker

1. Build the Docker image:

   ```bash
   docker build -t nodejs-demo-app .
   ```

2. Run the Docker container:

   ```bash
   docker run -p 3000:3000 nodejs-demo-app
   ```

3. Visit `http://localhost:3000/` to see the app in action.

---

## 📁 Project Structure

```
nodejs-demo-app/
├── app.js          # Main Express server
├── Dockerfile      # Docker configuration
├── package.json    # Project metadata and dependencies
```

---

## 🧪 Example Output

**GET** `http://localhost:3000/`

```json
{ "message": "Hello World" }
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🙌 Acknowledgements

Created by [Pallavi Panjla](https://github.com/Pallavipanjla)

---

Happy Coding! 🚀
```

---

Let me know if you want to include a `.dockerignore`, Docker Compose setup, or GitHub Actions CI later!
