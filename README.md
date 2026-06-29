# Shared Shopping List App

A full-stack web application for creating, managing and sharing shopping lists between users.

The system allows users to register, log in, recover their password, create shopping lists, manage products and share lists with other users in different access modes. It was developed as an academic team project focused on full-stack web development, backend/frontend communication and access control.

## Features

* User registration and login.
* Password recovery flow.
* Creating, editing and deleting shopping lists.
* Adding, editing and removing products.
* Marking products as bought or not bought.
* Sharing shopping lists with other users.
* Access modes for shared lists:

  * edit mode,
  * read-only mode with limited item status interaction.
* Backend API used by the frontend.
* Persistent data storage in a relational database.

## Tech Stack

### Backend

* Java
* Spring Boot
* Hibernate
* MySQL
* Gradle

### Frontend

* Vue.js
* JavaScript
* HTML
* SCSS
* Vite

## Architecture

The project is split into two main parts:

```text
shopping-list/
├── backend/     # Java Spring Boot backend
└── frontend/    # Vue.js frontend
```

The frontend communicates with the backend through API endpoints. The backend handles authentication, business logic, access control and database operations.

## Main Domain Concepts

The application is based on three main domain entities:

* `User` — application user account,
* `ShoppingList` — shopping list owned or shared with users,
* `Item` — product entry assigned to a shopping list.

## My Role and Contributions

This was a team project. I contributed to selected parts of the application implementation and integration work.

My work involved understanding and working with a full-stack architecture consisting of a Spring Boot backend, a Vue frontend and a MySQL database. I participated in implementing and testing application features related to shopping list management, product handling and user workflows.

Through this project, I practiced:

* working with a Java Spring Boot backend,
* using Hibernate-based persistence,
* connecting frontend views with backend API endpoints,
* implementing CRUD-oriented application logic,
* reasoning about user authentication and access control,
* working in a team project structure with separate frontend and backend modules.

The project helped me better understand how a web application is structured across backend, frontend and database layers.

## Running Locally

### Backend

Configure the database connection in:

```text
backend/src/main/resources/application.properties
```

Then run the backend:

```bash
cd backend
./gradlew bootRun
```

On Windows:

```bash
cd backend
gradlew.bat bootRun
```

### Frontend

Install dependencies and start the development server:

```bash
cd frontend
npm install
npm run dev
```

## Project Status

This is an academic portfolio version of a team project. The application demonstrates a full-stack shopping list system with authentication, list sharing, CRUD operations and backend/frontend integration.
