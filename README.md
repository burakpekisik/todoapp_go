# TodoApp (Go)

This project is a web-based application for managing and tracking To-Do tasks. The backend is built using Go, while the frontend uses React. The project demonstrates full-stack capabilities with user authentication, task management, and a responsive UI.

Founder of the project: https://www.youtube.com/watch?v=lNd7XlXwlho&t=3884s
Converted from Typescript to Javascript.

## Features

- **User Authentication**: Sign up and login functionality.
- **Task Management**: Create, edit, and delete to-do items.
- **Frontend**: React-based client for a smooth user experience.

## Getting Started

### Prerequisites

- Go 1.18+
- Node.js and npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/burakpekisik/todoapp_go.git
   ```

2. Install dependencies:
   ```bash
   go mod tidy
   cd client
   npm install
   ```

3. Run the backend:
   ```bash
   go run main.go
   ```

4. Run the frontend:
   ```bash
   cd client
   npm start
   ```

## Folder Structure

```plaintext
├── client/           # React frontend
├── cmd/              # Application entry point
├── config/           # Configuration files
├── db/               # Database schema and setup
├── routes/           # HTTP routes for API
└── utils/            # Helper functions
```

## How to Contribute

1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Open a pull request.

## License

This project is licensed under the MIT License.

---


