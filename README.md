# Abdel-Rahman Owais — Junior .NET Backend Developer

Building production-style backend systems with ASP.NET Core, C#, and SQL Server. Focused on Clean Architecture, CQRS, and scalable API design.

📫 abdoo.owais@gmail.com &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/eowais)

---

## 💼 Featured Project — Hospital ERP System

Healthcare management backend covering Pharmacy, Laboratory, Radiology, Patient Care, Doctor Management, and Hospital Administration, delivered through web and mobile clients.

**Architecture & key decisions**
- Clean Architecture + Vertical Slice Architecture, with CQRS via MediatR
- Mixed data-access strategy: **EF Core** for commands (Create/Update/Delete), **Dapper + stored procedures** for high-traffic read queries — chosen after comparing both for this project's read-heavy modules
- JWT authentication with role-based access control (RBAC) and bitmask-based permission flags
- FluentValidation for request validation · Swagger/Scalar for API documentation

**Stack:** ASP.NET Core Web API · C# · SQL Server · EF Core · Dapper · MediatR · Docker

🔗 [Repository](https://github.com/Dev0-0Team/Hospital-ERP-Backend)

<!-- TODO: add a screenshot or short GIF of the Swagger UI / a sample endpoint response here.
     A visual is the single biggest thing missing — it proves the API actually runs. -->

---

## 🛠 Tech Stack

| | |
|---|---|
| **Backend** | C#, ASP.NET Core Web API, LINQ |
| **Data** | SQL Server, T-SQL, EF Core, Dapper |
| **Architecture** | Clean Architecture, Vertical Slice Architecture, CQRS, MediatR, Repository Pattern |
| **Auth & Security** | ASP.NET Core Identity, JWT, Role-Based Authorization |
| **Tools** | Docker, Git & GitHub, Swagger / Scalar |

---

## 📝 Writing

I share what I'm learning about backend engineering and system design on [LinkedIn](https://linkedin.com/in/eowais) — recent posts cover EF Core vs. Dapper trade-offs and Clean Architecture layering.

---

📫 Open to Junior / Entry-Level Backend Developer opportunities — reach me at abdoo.owais@gmail.com
