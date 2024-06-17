# QuillQuest: Blogging Website


## Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Deployment](#deployment)
- [Demo](#demo)
- [Folder Structure](#folder-structure)
- [License](#license)


## Overview
QuillQuest is a feature-rich blogging platform designed to empower users to create, share, and manage their thoughts and ideas effortlessly. Whether you're a seasoned writer, a passionate blogger, or someone looking to share their expertise, QuillQuest offers a user-friendly interface coupled with powerful features to enhance your blogging experience.
QuillQuest is built with Node.js and MongoDB, utilizing Express.js for the backend and EJS for server-side templating. It features user authentication, CRUD operations for posts, comments, and a responsive design using Bootstrap.

## Tech Stack

- Express.js: Node.js web application framework for building the backend server.
- EJS: Embedded JavaScript templates for server-side rendering.
- Node.js: JavaScript runtime environment.
- MongoDB: NoSQL database for storing blog posts and user data.
- Bootstrap: Frontend framework for responsive design.

## Features

- CRUD Operations: Users can Create, Read, Update, and Delete blog posts.
- RESTful APIs: Built with Express.js to provide a RESTful API interface for interacting with blog posts.
- MongoDB: Uses MongoDB to store blog post data.
- Bootstrap: Frontend framework for responsive design and UI components.

## Deployment
This project is deployed on Render for production. Render provides scalability and reliability for hosting web applications.


## Demo

[https://quillquest-1b3t.onrender.com](https://quillquest-1b3t.onrender.com/)

## Folder Structure


```bash
QuillQuest/
│
├── init/
│ └── data.js
│ └── index.js
│
├── models/
│ ├── listing.js
│
├── public/css/
│ ├── style.css
│
├── viewss/
│ ├── includes/
│   ├── footer.ejs
│    ├── navbar.ejs
│
│ ├── layouts/
│    ├── boilerplate.ejs
│
│ ├── listings/
│    ├── About-us.ejs
│   ├── edit.ejs
│   ├── index.ejs
│   ├── new.ejs
│   ├── show.ejs
│
├── .gitignore
├── LICENSE
├── app.js
├── package-lock.json
└── package.json
```

## License

This project is licensed under the MIT License.

<h4 align='center'>Developed By <b><i>Sristy Paul</i></h4>
