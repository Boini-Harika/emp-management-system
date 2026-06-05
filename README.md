# EmpTrack — Employee Management System

A full-stack web app to manage employee records with full CRUD operations.

## Tech Stack
- **Frontend:** React (Vite), Axios, React Router, Bootstrap
- **Backend:** Spring Boot, Spring Data JPA, MySQL
- **Deployed:**  Railway

## Features
- View, Add, Edit, and Delete employees
- Form validation with error messages
- Responsive UI with clean gradient design

## API Endpoints
| Method | Endpoint | Description |

| GET | `/api/v1/employees/employees` | Get all employees |
| POST | `/api/v1/employees/add` | Add employee |
| PUT | `/api/v1/employees/update/{id}` | Update employee |
| DELETE | `/api/v1/employees/delete/{id}` | Delete employee |

## Run Locally

**Backend**
```bash
# Set environment variables
SPRING_DATASOURCE_URL=jdbc:mysql://localhost:3306/employeedb
SPRING_DATASOURCE_USERNAME=root
SPRING_DATASOURCE_PASSWORD=yourpassword

./mvnw spring-boot:run
```

**Frontend**
```bash
npm install
npm run dev
```

## Author
**Harika** — MCA Graduate | Full Stack Developer | Hyderabad
