# MERN Stack Application with Git-Based DevOps Workflow

## 📦 Overview

This project demonstrates a MERN (MongoDB, Express.js, React, Node.js) stack application structured and managed using Git best practices. 
The goal was to simulate a real-world DevOps workflow involving Git branching, pull requests, tagging, and Docker-based deployment.

---

## 📁 Project Structure

Task_3_Internship_/

├── backend/ # Node.js + Express API

├── frontend/ # React.js frontend

└── docker-compose.yml

---

## 🚀 Key Steps and Workflow

### 1. **Branching Strategy**

- **Frontend Branch**: A dedicated `frontend` branch was created to manage all frontend-related development.
- **Backend Branch**: A separate `backend` branch was maintained for backend APIs and logic.
- Each component was isolated to ensure better code organization and focused development.

### 2. **Development & Commits**

- All development changes were tracked using the **Git CLI**.
- Each feature was committed and pushed to its respective branch (`frontend` or `backend`).

### 3. **Merge via Pull Requests**

- After completing development in both branches, **pull requests** were created to merge the changes into the `main` branch.
- This approach ensures a clean and reviewed integration of features.

### 4. **Version Tagging for Release**

- Once merged into `main`, the project was tagged with:
  - `v1.0` – representing the first stable release of the full-stack application.

### 5. **Docker Integration**

- A `docker-compose.yml` file was added to support containerization and simplify multi-container deployment for both backend and frontend services.

### 6. **Final Tagging**

- After successfully integrating Docker and validating the entire stack, a final version tag was created:
  - `FinalVersion` – marking the completion of the project.

---

## 🐳 Docker Deployment

To run the full-stack application using Docker Compose:

```bash
docker-compose up --build
