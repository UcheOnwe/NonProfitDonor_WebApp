# Nonprofit Donor Management Web App

A Blazor Server web application for managing donors, donations, and nonprofit records.  
Built using C#, SQL Server, Entity Framework Core, and Radzen UI components.
This project demonstrates full-stack C# development, database integration, CRUD operations, and UI design.

## Features
### Donor Management
- Add new donors

- Validate donor form fields

- Display all donors in a DataGrid

- Auto-generated database entities from SQL schema

- SQL Server LocalDB using EF Core

### Database
- Multiple tables: Donor, Donation, DonationCategory, Expense, etc.

- Relational database with primary & foreign keys

- Reverse-engineered entity models using EF Core Power Tools

- ER relationship diagram included

### Front-End (Blazor + Radzen)
- Responsive donor form

- Validation warnings

- Auto-refresh table

- Clean UI layout using Radzen components
  
## Tech Stack
- Front-end (Blazor Server, Radzen UI)
- Back-end (C# (.NET 8), Entity Framework Core)
- Database(SQL Server LocalDB)
- Tools (Visual Studio 2022, EF Core Power Tools)
- Version Control (Git + GitHub)

## Project Demo Videos
- **Early UI Demo - Donors, Donations & Categories**
 https://youtu.be/G9mieZYUmSg
- **Full Application Demo - Expense & Expense Categories** 
## Project Structure
- /Components
- /Models
- /Pages
- /wwwroot
- /Screenshots
- Program.cs
- appsettings.json
- B7.csproj


## How to Run
1. Clone the repository:   git clone https://github.com/UcheOnwe/NonProfitDonor_WebApp.git

2. Open the solution in Visual Studio 2022
3. Ensure you have:
 .NET 8 SDK
  SQL Server LocalDB  
4. Update the connection string in "appsettings.json"  
5. Run the application  

## Future Improvements
- Add donations & expenses pages

- Add user authentication

- Add reporting dashboard

- Convert into a full CRUD system for all tables

## Author
- Uchechukwu Onwe.
- Computer Science - Texas A&M University - Victoria.
- Passionate about backend development, C#, Blazor, SQL, and building real-world apps.
