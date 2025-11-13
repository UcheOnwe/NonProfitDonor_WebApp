NonProfit Donor Management Web App

A Blazor Server web application for managing non-profit donors, recording donor information, tracking submissions, and displaying records using SQL Server LocalDB, Entity Framework Core, and Radzen UI components.

This project demonstrates full-stack C# development, database integration, CRUD operations, and UI design.

🚀 Features
✅ Donor Management

Add new donors

Validate donor form fields

Display all donors in a DataGrid

Auto-generated database entities from SQL schema

SQL Server LocalDB using EF Core

📊 Database

Multiple tables: Donor, Donation, DonationCategory, Expense, etc.

Relational database with primary & foreign keys

Reverse-engineered entity models using EF Core Power Tools

ER relationship diagram included

🖥️ Front-End (Blazor + Radzen)

Responsive donor form

Validation warnings

Auto-refresh table

Clean UI layout using Radzen components

🛠️ Tech Stack
Layer	Technology
Front-end	Blazor Server, Radzen UI
Back-end	C# (.NET 8), Entity Framework Core
Database	SQL Server LocalDB
Tools	Visual Studio 2022, EF Core Power Tools
Version Control	Git + GitHub
📂 Project Structure
/Components
/Models
/Pages
/wwwroot
/Screenshots
Program.cs
appsettings.json
B7.csproj

📸 Screenshots
Add Donor Form

Donor List / Display

Donor Submitted Notification

Validation Warning

Database Relationship Diagram

⚙️ How to Run the Project

Clone the repository:

git clone https://github.com/UcheOnwe/NonProfitDonor_WebApp.git


Open the solution in Visual Studio 2022

Ensure you have:

.NET 8 SDK

SQL Server LocalDB

Update the connection string in appsettings.json (if needed)

Run the project (Ctrl + F5)

📈 Future Improvements

Add donations & expenses pages

Add user authentication

Add reporting dashboard

Convert into a full CRUD system for all tables

👤 Author

Uchechukwu Onwe
Computer Science — University of Houston-Victoria
Passionate about backend development, C#, Blazor, SQL, and building real-world apps.
