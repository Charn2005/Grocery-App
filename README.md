1. Project Overview:
This project is a Smart Grocery Shopping App built using ASP.NET MVC. It allows users to browse products, add them to the cart, place orders, and track status.

2. Requirements:
Before running the project, make sure you have these installed:
Visual Studio 
Git (for version control)

3. Clone the Repository:
First, clone the project from GitHub:
git clone <repository-url>

4. Set Up the Database in Visual Studio:
Open appsettings.json and add your database connection string:

"ConnectionStrings": {
    "DefaultConnection": "Server=your-server;Database=Your-database-name;Trusted_Connection=True;"
}

5. Install Dependencies:
Go to Tools tab and then click on nuget package manager and further click on manage nuget packages for solution. Then, install Microsoft.EntityFrameworkCore.Tools and Microsoft.EntityFrameworkCore.SqlServer packages.

6. Open package manager console and add migrations by running:
   Add-Migration Setup
   
   Then update the database with:
   update-database
   
7. Run the Application.

8. Testing the App:
Once the app is running, you can:

Register as a user
Browse products
Add items to the cart
Place an order

This documentation will help you set up the Grocery Shopping App and get it running on your machine. 
