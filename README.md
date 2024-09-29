Richfield PC Store System
This system is designed to assist Richfield IT students in purchasing PC components by providing a seamless transaction experience. The system uses VB.NET and MS Access to manage the pricing, transaction processing, and user management. Below are the key features and functions of the system.

Key Features
1. Login and Signup System
Login Form: Validates user credentials against the login_details table in the database.

Table Structure:
ID (Primary Key, Number)
Name (Text)
Lastname (Text)
Date of Birth (Date)
Gender (Text)
Username (Text)
User_Image (Image)
Password (Text)
If login details are incorrect, users can choose the Signup option.
Signup Form: Allows new users to register and stores data in the login_details table.

2. Main Transaction Form
After successful login, the system presents a transaction form with the following features:

Price Calculation: Prices are automatically displayed when an item is selected from a combobox.
Transaction Details: The system calculates and displays:
Subtotal
VAT
Discount (based on the type of purchase)
Total price
Transaction slip displayed in a rich text box.
Buttons:
Logout: Redirects users back to the login form.
Compute: Calculates the total cost, including discounts and VAT.
Reset: Clears the current form.
Print: Prints the transaction slip.
New Stock: Opens a form to add new stock items.
New User: Opens a form to add a new user.
3. Administrator Features
New User Management: Administrators can add new users via a form with two tabs:

Personal Information (stored in login_details table):
ID (Primary Key)
Name, Lastname, Date of Birth, Gender, Username, Password, and User Image.
Additional Details (stored in the more_details table):
Address, Contact Number, Qualification, and Net Profit.
Data Management:

Admins can add, delete, update, and view user and stock details in the database using a data grid view.
Database Integration
The system is connected to an MS Access database called RGI Tech Store, which handles user login details, stock management, and transaction history.

Usage Instructions
Login or Signup to access the transaction form.
Select Items from the combobox to view prices and perform calculations.
Admins can manage stock and user details through designated forms.
This system simplifies component purchasing for Richfield students while ensuring security and ease of use through an integrated database.
