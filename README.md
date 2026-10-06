# Quora Posty REST API

A Quora-like REST project built using **Node.js, Express.js, and EJS**.

## Technologies Used

- Node.js
- Express.js
- EJS
- UUID
- HTML
- CSS
- JavaScript

## Features

- View all posts
- Create a new post
- View individual posts in detail
- Generate unique post IDs using UUID
- Update post content using PATCH requests
- EJS templates for dynamic pages
- Static CSS styling

## REST Routes

| Method | Route | Description |
|---|---|---|
| GET | `/posts` | View all posts |
| GET | `/posts/new` | Open the create-post form |
| POST | `/posts` | Create a new post |
| GET | `/posts/:id` | View a specific post |
| PATCH | `/posts/:id` | Update a post |

## Project Structure

```text
RESTCLASS/
│
├── public/
│   └── style.css
│
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   └── show.ejs
│
├── index.js
├── package.json
├── package-lock.json
└── .gitignore
```

## Concepts Learned

- Express.js server setup
- Routing
- Middleware
- EJS
- Dynamic routes
- Request parameters
- POST requests
- PATCH requests
- UUID
- REST API concepts
- Static files and CSS
- EJS dynamic data

## How to Run

### 1. Install dependencies

```bash
npm install
```

### 2. Start the server

```bash
node index.js
```

### 3. Open the project

```text
http://localhost:8080/posts
```

## Author

**Shruti Zade**

GitHub: **shrutizade05-ux**