# Book Store MERN Project

A simple project using JavaScript and the MERN (MongoDB, Express, React, Node.js) stack. This application simulates a book store, allowing users to manage books and view book details.

## Features

- **Backend**: Express server with RESTful APIs
- **Frontend**: React application for a dynamic user interface
- **Database**: MongoDB for storing book information and user data

## Prerequisites

- [Node.js](https://nodejs.org/en)
- [MongoDB](https://www.mongodb.com/)

## Getting Started

### Clone the Repository

```shell
git clone https://github.com/loganengle/bookstore-MERN.git
cd bookstore-MERN
```

### Set Up the Backend

#### 1. Navigate to the backend directory:

```shell
cd backend
```

#### 2. Install the required dependencies:

```shell
npm install
```

#### 3. Configure MongoDB:

In `config.js` update the `mongoDBURL` constant with your MongoDB connection string.

```shell
npm install
```

#### 4. Start the backend server:
```shell
npm run dev
```

### Set Up the Frontend

#### 1. Navigate to the frontend directory:

```shell
cd frontend
```

#### 2. Install the required dependencies:

```shell
npm install
```

#### 3. Start the frontend application:
```shell
npm run dev
```

## Usage

- **Frontend**: Browse and interact with the book store interface.
- **Backend**: Access the APIs to fetch and manage book data (e.g., GET /api/books, POST /api/books).