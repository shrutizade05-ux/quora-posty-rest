# Quora Posty REST API

A Quora-like REST project built using **Node.js, Express.js, and EJS**.

## Technologies Used

- Node.js
- Express.js
- EJS
- UUID
- Method-Override
- HTML
- CSS
- JavaScript

## Features

- View all posts
- Create new posts
- Submit new posts
- View individual posts in detail
- Generate unique post IDs using UUID
- Edit existing posts
- Update post content using PATCH requests
- Delete posts using DELETE requests
- Dynamic pages using EJS
- Static CSS styling
- Separate edit page with CSS styling

## REST Routes

| Method | Route | Description |
|---|---|---|
| GET | `/posts` | View all posts |
| GET | `/posts/new` | Open the create-post form |
| POST | `/posts` | Create a new post |
| GET | `/posts/:id` | View a specific post |
| GET | `/posts/:id/edit` | Open the edit-post form |
| PATCH | `/posts/:id` | Update a post |
| DELETE | `/posts/:id` | Delete a post |

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
│   ├── show.ejs
│   └── edit.ejs
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
- EJS templates
- Dynamic routes
- Request parameters
- POST requests
- PATCH requests
- DELETE requests
- UUID
- Method-Override
- REST API concepts
- Static files
- CSS styling
- CRUD operations

## How to Run

### 1. Install dependencies

```bash
npm install
```

### 2. Start the server

```bash
node index.js
```

### 3. Open in browser

```text
http://localhost:8080/posts
```

## Author

**Shruti Zade**

GitHub: **shrutizade05-ux**