# Employee Leave Management System
An end-to-end, data-driven web application that enables employees to submit leave requests and allows administrators to manage and approve these requests. This project is built using the modern, cross-platform ASP.NET Core framework, providing a robust and scalable solution for managing employee leaves.

## Features
* **User Authentication & Authorization:**
Secure user login and registration using ASP.NET Core Identity. Role-based access control is implemented so that administrators and employees can access functionalities tailored to their permissions.

* **Leave Request Management:**

* **Submission:** Employees can submit leave requests, view the status of their requests, and track leave balances.

* **Approval Workflow:** Administrators have a dedicated interface to review, approve, or reject leave requests. Detailed request histories are maintained for audit purposes.

* **Data-Driven Architecture:**

  * Entity Framework Core Code-First: Define your data models and relationships with migrations to automatically build and update the database schema.

  * Repository & Unit of Work Pattern: Abstract data access and encapsulate business logic to improve code maintainability and testability.

* **Responsive User Interface:**
Use of Bootstrap and jQuery ensures a mobile-friendly and dynamic experience for users, with modern, clean UI layouts for all screens.

* **API Integrations & Third-Party Services:**
Integration with external libraries and services for email notifications, ensuring seamless communication for leave request updates.

* **Deployment Ready:**
The application is fully configured for deployment on Internet Information Services (IIS) as well as Microsoft Azure App Services, with automated build/release pipelines managed through GitHub and Azure DevOps.

## Technology Stack
* **Backend Framework:** ASP.NET Core 9

* **Programming Language:** C#

* **Data Access:** Entity Framework Core using Code-First approach, Repository Pattern, and Unit of Work

* **Authentication:** ASP.NET Core Identity

* **Frontend:** MVC Architecture, Bootstrap, jQuery, and other front-end libraries for a responsive design

* **Database:** Microsoft SQL Server

* **Development Environment:** Visual Studio with NuGet Package Manager for dependency management

* **Deployment:** Configured for IIS and Microsoft Azure (Web and SQL services), with CI/CD pipelines using GitHub and Azure DevOps

* **Additional Tools:** AutoMapper for mapping between data models and view models, asynchronous programming for performance optimization
