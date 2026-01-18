# HomelyHub

HomelyHub is a full-stack web application built to explore **backend system design, role-based access control, and data consistency** in a multi-user environment.

The project focuses on **engineering correctness, clean APIs, and scalable backend structure**, rather than UI complexity.

---

## Motivation
Many real-world applications require:
- multiple user roles with different permissions
- secure authentication and authorization
- consistent data handling across users
- clear separation between business logic and persistence

HomelyHub was built to implement and reason about these concerns in an end-to-end system.

---

## Architecture
The application follows a standard **client–server architecture**:

- **Frontend**: React-based client for user interaction
- **Backend**: Node.js + Express REST API enforcing authentication and authorization
- **Database**: MongoDB with schema-driven design

Backend code is organized to keep routing, business logic, and data models loosely coupled.

---

## Key Features
- Role-based authentication and authorization
- Secure login and access control via middleware
- RESTful API design with clear resource boundaries
- Modular backend structure for maintainability
- Database schemas designed for consistency and integrity

---

## Engineering Focus
This project emphasizes:
- **Correctness**: preventing unauthorized access and invalid state
- **Scalability**: API and data model design that can evolve with usage
- **Maintainability**: clean abstractions and separation of concerns

The goal was to understand system behavior under realistic usage and edge cases.

---

## Tradeoffs
- Prioritized clarity and correctness over aggressive optimization
- Designed for learning and experimentation, not production deployment
- Limited frontend complexity to keep focus on backend engineering

---

## Tech Stack
- MongoDB
- Express.js
- React
- Node.js

---

## Running Locally
```bash
# install dependencies
npm install

# start backend
npm run server

# start frontend
npm start
