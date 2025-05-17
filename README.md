# Contractor Management System

This is a full-stack web application built using **ASP.NET Core Web API**, **Entity Framework (Database First)**, and **Razor Pages**. It is designed for contractors to efficiently manage projects, generate quotations, handle billing, and search project details.

## 🔧 Features

- Create new contractor projects
- Add multiple work items with details like rate, quantity, and measurement type
- Generate and save quotations
- Generate final bills after completing the work
- Search project details using Project ID
- Store all data securely in a SQL Server database

## 🛠️ Technologies Used

- ASP.NET Core Web API
- Razor Pages
- Entity Framework (Database First)
- SQL Server
- C#
- HTML/CSS (basic UI styling)

## 📁 Project Structure

- **Models** – Contains data models like `Quotation`, `WorkDetail`, and `Bill`
- **DbContext** – `AjantaDbContext.cs` manages database interaction using EF
- **Pages** – Razor Pages for UI (Home, Create Quotation, Generate Bill, Search)
- **Controllers** – Web API endpoints for backend operations

## 🏗️ Real-World Use Case

This system was built for **Ajanta Interior Decorators**, a real-world contractor. The goal was to digitize their manual process of project estimation, quotation generation, billing, and record maintenance.

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ContractorManagementSystem.git
