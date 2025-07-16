# Note For Web Architecture

---

## Main Components of a Web Application:

| Component   | His Role                                              |
|-------------|---------------------------------------------------------------|
| Client      | The user's device/browser that sends requests                 |
| Server      | Receives the request, processes it, and sends back a response |
| Database    | Stores application data (e.g., users, products)               |
| API         | Communication bridge between client and server                |

---

## Request Lifecycle:

1. User opens a browser and enters a URL.
2. The browser sends an HTTP request to the server.
3. The server processes the request and fetches data from the database if needed.
4. The server returns an HTML/CSS/JS response.
5. The browser renders the webpage for the user.

---

### 3. Three-Tier Architecture (Standard in Modern Apps)
- Separates the application into three independent layers:

#### a. Presentation Layer (Frontend/UI)
- Handles user interface and interaction
- Built using HTML, CSS, JavaScript

#### b. Business Logic Layer (Application Layer)
- Contains the app's core logic and functionality
- Built using backend technologies like Java, Node.js, Django

#### c. Persistence Layer (Data Layer)
- Responsible for storing and retrieving data
- Uses SQL or NoSQL databases (e.g., MySQL, MongoDB)


## Web Application Architectures:

### 1. Monolithic:
- All code (frontend, backend, DB) in a single unit.
- Simple to start with, but hard to scale and maintain.

### 2. Two-Tier:
- Client communicates directly with a backend server.
- The backend handles database interactions.

### 3. Three-Tier:
- Separates frontend, backend, and database through APIs.
- More modular and scalable.

### 4. Microservices:
- Each feature (e.g., login, products) is a separate service.
- Highly scalable, used in large applications.

---


## Architecture Comparison:

| Architecture    | Easy to Develop | Scalable | Complexity |
|-----------------|------------------|----------|------------|
| Monolithic      | Yes              | No       | Low        |
| Three-Tier      | Moderate         | Yes      | Medium     |
| Microservices   | Hard             | Yes      | High       |

---

## Key Concepts and Tools:

| Concept       | Description                           |
|---------------|---------------------------------------|
| HTTP Methods  | GET, POST, PUT, DELETE                |
| JSON          | Lightweight format for data transfer  |
| REST API      | Common style for APIs                 |
| AJAX / Fetch  | Update page content without reloading |

---

## Frontend vs Backend:

| Part      | Responsibility                     | Common Tools           |
|-----------|-------------------------------------|-------------------------|
| Frontend  | User interface and client-side logic | HTML, CSS, JavaScript   |
| Backend   | Business logic and data processing  | Node.js, Java, Django   |
| Database  | Data storage and retrieval          | MySQL, PostgreSQL, MongoDB |

---

## Summary:

- A web app is built from client, server, database, and APIs.
- Different architectures suit different project needs.
- Understanding how the web works is essential before diving into frameworks