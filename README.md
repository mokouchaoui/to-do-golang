# Todo Application with Go & React

This project demonstrates how to build a basic Todo Application using Go for the server, Fiber as the Go web server, Vite for the client, Mantine for React components, and TypeScript for static typing. By following this project, you will learn how to create a RESTful API with Go, develop a user interface for managing todos in React with TypeScript, and use Mantine for some basic UI components.

## Technologies Used

- **Go**: The server-side code is written in Go, a statically-typed, compiled language known for its performance and simplicity.
- **Fiber**: Fiber is a web framework for Go that provides fast and flexible routing and middleware support.
- **Vite**: Vite is a fast build tool and development server for JavaScript applications. In this project, it's used to build the client-side code.
- **Mantine**: Mantine is a React component library that offers a wide range of well-designed components to simplify UI development.
- **TypeScript**: TypeScript is used for static type checking, making your code more robust and maintainable.

## Getting Started

### Prerequisites

Before you start, make sure you have the following software installed on your machine:

- Go: [Download and Install Go](https://golang.org/doc/install)
- Node.js and npm: [Download and Install Node.js](https://nodejs.org/)

### Installation


# Clone this repository
```bash
git clone https://github.com/mokouchaoui/to-do-golang
cd to-do-golang
```
# Install server dependencies
```bash

cd server
go get -d ./...
```

# Install client dependencies
```bash

cd ../client
npm install
```

# Running the Application

```bash
# Start the server
cd ../server
go run main.go

The server will be available at [http://localhost:3001].(http://localhost:3001).

# Start the client

```bash
cd ../client
npm run dev
```

The client will be available at [http://localhost:3000].(http://localhost:3000).

## Usage

- Visit http://localhost:3000 in your browser to access the Todo Application.
- You can add, edit, and delete todos.
- The server provides RESTful API endpoints for managing todos.

## Project Structure

- `server/`: Contains the Go server code.
  - `main.go`: Entry point for the server.
  - `handlers/`: Contains HTTP request handlers for todos.
  - `models/`: Defines the data models.
- `client/`: Contains the React client code.
  - `src/`: React components and TypeScript code.
  - `public/`: Static assets.

## Learning Objectives

By working with this project, you will gain knowledge and experience in the following areas:

- Creating a basic Go REST API.
- Building a Todo UI using React and TypeScript.
- Using Mantine for basic UI components.


