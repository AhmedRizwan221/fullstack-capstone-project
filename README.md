# IBM Full-Stack JavaScript Developer – Final Capstone Project

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

## 📌 Overview

This repository contains my final capstone work for the
**IBM Full-Stack JavaScript Developer Professional Certificate** on Coursera.

Throughout the course, I completed hands-on labs and practical tasks covering frontend development, backend development, databases, containerization, DevOps practices, and application deployment. The capstone project brought these concepts together in a full-stack JavaScript application.

The repository includes the frontend and backend components of the application, along with supporting coursework, Agile documentation, and deployment configurations.

---

## 🚀 Project: GiftLink

GiftLink is a full-stack web application consisting of:

- A React frontend application
- A Node.js / Express backend application
- A MongoDB database
- REST API integration between frontend and backend
- A containerized development environment

---

## 🎯 Learning Objectives

Through this project, I practiced:

- Building frontend interfaces
- Developing backend REST APIs
- Working with databases
- Implementing CRUD operations
- Using Git and GitHub
- Writing user stories and following an Agile workflow
- Containerizing applications with Docker
- Working with development and deployment workflows
- Exploring Kubernetes-based deployment

---

## 🛠️ Technologies Used

- JavaScript
- React.js
- Node.js
- Express.js
- MongoDB
- REST APIs
- Git & GitHub
- Docker
- Kubernetes
- Postman

---

## 📂 Project Structure

```text
├── .github/              # GitHub configuration
├── Alsubmission/         # Course submission material
├── giftlink-backend/     # Node.js / Express REST API
├── giftlink-frontend/    # React frontend
├── sentiment/            # Supporting coursework
├── .gitignore
├── .jshintrc
├── LICENSE
├── README.md
├── deploymongo.yml       # Kubernetes configuration for MongoDB
└── userstory.md          # User stories for the project
```

---

## 📚 Course Labs & Practical Work

### Frontend Development
- Built and modified web interfaces
- Worked with React and JavaScript
- Practiced component-based development
- Worked on frontend–backend integration

### Backend Development
- Built RESTful APIs
- Implemented CRUD operations
- Worked with Node.js and Express.js
- Tested API endpoints with Postman

### Database
- Worked with MongoDB
- Connected backend applications to the database
- Performed database operations

### DevOps & Containers
- Created Docker images
- Worked with Docker containers
- Configured application environments
- Practiced container-based development

### Kubernetes
- Explored Kubernetes concepts
- Worked with Pods and Services
- Attempted to deploy the application using Kubernetes

---

## 📋 Agile Development & User Stories

As part of the project workflow, I created user stories based on the application requirements and organized them into an Agile workflow.

The user stories were initially managed in the **Icebox** and then moved into the **Backlog** as they were prioritized for implementation. The stories are documented in [`userstory.md`](./userstory.md).

This helped me practice:

- Writing user stories
- Requirement analysis
- Backlog management
- Task prioritization
- Agile development workflow

---

## 🗄️ Database

MongoDB is used as the database for the application.

For local development and testing, I used the **official MongoDB Docker image** to run MongoDB as a container. This allowed the backend application to connect to a containerized MongoDB instance throughout development.

A Kubernetes configuration file, [`deploymongo.yml`](./deploymongo.yml), was also created as part of the deployment-related coursework.

---

## 🐳 Docker

The application was containerized and tested using Docker. I also used Docker Desktop locally to understand the containerization and deployment workflow.

---

## ☸️ Kubernetes Deployment

As part of the final course lab, the project was intended to be deployed using Kubernetes.

I attempted the Kubernetes deployment locally using Docker Desktop. The MongoDB workload ran successfully, but the backend workload encountered deployment/runtime issues that I was unable to resolve within the lab environment. **The final Kubernetes deployment was therefore not completed.**

This repository documents the work that was successfully completed, as well as the deployment stage that I explored but did not fully finish.

---

## 💡 What I Learned

This project strengthened my understanding of:

- Full-stack JavaScript development
- Frontend and backend integration
- REST API development
- Database integration
- Git/GitHub workflows
- Agile practices and user stories
- Docker containerization
- Kubernetes fundamentals
- Debugging and troubleshooting application deployments

---

## 📄 License

This project is licensed under the terms of the [LICENSE](./LICENSE) file included in this repository.
