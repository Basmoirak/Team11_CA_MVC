# gdipsa-ASP.NET MVC

## Project: To create a "software sales" web application with shopping cart functionality

## Installation Instructions
- Build Team11_MVC Solution
- Install Entity Framework 6.2.0 using NuGet Package Manager
- Run the Enable-Migrations command in Package Manager Console to connect to your local SQL Server
- Run the Add-Migration InitialMigration command in Package Manager Console
- Run the Update-Database command in Package Manager Console to generate tables and seed data into your SQL Server
- https://docs.microsoft.com/en-us/ef/ef6/modeling/code-first/migrations/

## Known Errors during installation
- Solution will sometimes fail to run properly due to a bug in Microsoft.CodeDom.Providers.DotNetCompilerPlatform package 1.0.7. You can    refer to the link below for a solution to fix the error.
- https://blogs.msdn.microsoft.com/jpsanders/2018/02/22/error-could-not-find-a-part-of-the-path-esitesroot0binroslyncsc-exe/

## To Login 
- Username: customer1 | Password: customer1 
- Username: customer2 | Password: customer2

## Features

**Login & Registration**
- Users can login and register, and all users will have their passwords hashed in the database.
- Appropriate error messages will be displayed via data annotations

**Product Gallery Page**
- Users can search for products hitting enter in the searchbar
- Users can view their names and logout of the system in the navigation bar at the top
- Users can click on My Purchases to view his past purchase history
- Users can add products to the shopping cart, and view the total count and amount in the shopping cart

**Shopping Cart**
- Users can view existing items in the shopping cart from previous sessions
- Users can update the quantity or remove existing items in the shopping basket
- Users can clear all items in the basket
- Users can click checkout to make payment

**Checkout Page**
- Users will be redirected to the list of the items that were purchased in the current session

**My Purchase History Page**
- Users can view his entire purchase history, and view software activation codes in the combo box




