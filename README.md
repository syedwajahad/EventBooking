✅ Features

🔒 Authentication & Authorization

📅 Event Management: Create, Update, Delete, Publish, Unpublish events

📥 Booking System: Reserve seats for events

🧠 CQRS using MediatR for clear command-query separation

🧪 Unit Testing using xUnit & FluentAssertions

🔄 Entity Framework Core integration with SQL Server

🧱 Tech Stack

.NET 8 / ASP.NET Core Web API

MediatR (CQRS implementation)

Entity Framework Core

AutoMapper

FluentValidation

SQL Server

Swagger for API documentation

🔃 Architecture

API – Entry point (controllers)

Application – Business logic, CQRS handlers, validators

Domain – Core entities and enums

Infrastructure – EF Core DbContext, Repositories, persistence

Persistence – Implementation of repository interfaces


🚀 Endpoints

GET /api/events – Get all events (with optional filters)

GET /api/events/{id} – Get event by ID

POST /api/events – Create a new event

PUT /api/events/{id} – Update an event

DELETE /api/events/{id} – Delete an event

PUT /api/events/{id}/publish – Publish event

PUT /api/events/{id}/unpublish – Unpublish event
