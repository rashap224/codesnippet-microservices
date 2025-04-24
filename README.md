
# Code Snippet Manager (Microservices Architecture)

This is a simple yet scalable full-stack application that allows users to post and comment on code snippets. Built with React (Vite) on the frontend and Node.js (Express) with a microservices approach on the backend.

## 🔧 Tech Stack

- **Frontend:** React (Vite)
- **Backend:** Node.js, Express.js
- **Architecture:** Microservices-based (modular services)
- **State Management:** Local JSON, no database used yet

## 📸 Screenshots

| Snippet JSON Data | Web UI |
|-------------------|--------|
 | ![Backend](<Screenshot 2025-04-24 170922.png>) | ![Frontend](<Screenshot 2025-04-24 165545.png>) |
## 📁 Microservices Structure

- `snippet-service`: Manages code snippets and basic comment logic.
- `comment-service`: Manages comments for each snippet.
- `api-gateway`: Acts as a centralized entry point (planned for future).
- (Planned) `broker-service`: For inter-service communication using a message broker like RabbitMQ.

## 🚀 Features

- Add code snippets with titles and descriptions.
- Add and view comments on each snippet.
- JSON-based response for API testing.
- Prepared for future scalability with containerization and message brokers.

## 🧑‍💻 Getting Started

### Install

```bash
npm install
```

### Run Frontend

```bash
cd client
npm run dev
```

### Run Backend Services

```bash
cd snippet-service
npm start

cd comment-service
npm start
```

### Project URL

> http://localhost:5173


