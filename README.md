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

This was an academic team project. I contributed to selected backend/frontend integration tasks and worked with the application structure across the Spring Boot backend, Vue frontend and MySQL database.

My work included:

* working with DTO-based request and response structures,
* connecting selected frontend views with backend API endpoints,
* supporting CRUD-oriented flows for shopping lists and products,
* testing user scenarios related to list management, product handling and shared access,
* working with the backend structure based on controllers, services, Hibernate entities and repositories,
* helping verify authentication and access-control related behavior from the user workflow perspective.

The project helped me practice building and integrating a full-stack web application with separate backend, frontend and database layers. It also gave me practical experience with Java/Spring-based backend development, REST-style communication and team project organization.

