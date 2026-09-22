# 🎓 Student Management RESTful API

A clean and maintainable **RESTful Web API** built with **C#** and **ASP.NET Core**, adhering strictly to **3-Tier Architecture** patterns.

## 🏗️ Architecture Overview

The project is structured into three distinct layers to ensure clear separation of concerns (SoC) and testability:

1. **Presentation Layer (API Controller):** Handles HTTP Requests/Responses, Data Validation, and Endpoints Routing.
2. **Business Logic Layer (BLL):** Enforces business rules and manages data transformations via DTOs.
3. **Data Access Layer (DAL):** Responsible for directly communicating with the underlying data storage or simulation models.

---

## 🛠️ Tech Stack & Features

* **Framework:** ASP.NET Core Web API (.NET)
* **Language:** C#
* **Architecture:** 3-Tier Architecture (Presentation, Business, Data Access)
* **Design Pattern:** Data Transfer Object (DTO)
* **API Documentation:** Swagger / OpenAPI

---

## 🚀 API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/api/Students/All` | Retrieve all registered students |
| **GET** | `/api/Students/Passed` | Retrieve list of students who passed |
| **GET** | `/api/Students/AverageGrade` | Calculate the average grade of all students |
| **GET** | `/api/Students/{id}` | Get specific student details by ID |
| **POST** | `/api/Students` | Add a new student |
| **PUT** | `/api/Students/{id}` | Update existing student information |
| **DELETE** | `/api/Students/{id}` | Remove a student record |

---

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/StudentApiProject.git](https://github.com/YOUR_USERNAME/StudentApiProject.git)
   ```
2. Open the solution in **Visual Studio 2022**.
3. Set `StudentApiProject` as the Startup Project.
4. Press `F5` or Run the application to open the **Swagger UI**.
