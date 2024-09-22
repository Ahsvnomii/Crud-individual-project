# Basic CRUD Application Using C# and Windows Forms

## Overview
This project is a basic CRUD (Create, Read, Update, Delete) application developed using C# with Windows Forms as a user interface. It allows users to manage records in a database by performing the following operations:
- Adding new records.
- Retrieving/displaying records.
- Updating existing records.
- Deleting records.

### Key Features
- *Create*: Add new records to the database through an input form.
- *Read*: Display existing records in a table or list.
- *Update*: Modify details of existing records.
- *Delete*: Remove records from the system.

### Tools and Technologies
- *Programming Language*: C#
- *User Interface*: Windows Forms (WinForms)
- *Database*: Microsoft SQL Server
- *IDE*: Visual Studio

## Project Workflow

### 1. User Interface (Windows Forms)
- *Add/Edit Form*: A separate form to enter or modify record details.
- *Message Boxes*: Used for confirming actions such as deletion or record creation.

### 2. Database Operations
- *Create*: Add a new record by submitting a form.
- *Read*: Fetch and display records from the database in the list or table view.
- *Update*: Edit an existing record by selecting it and submitting the modified data.
- *Delete*: Remove a record by selecting it and confirming deletion.

### Technical Steps

#### 1. Database Setup
1. Open the .mdf file located in the folder.
2. Create a new SQL Server database.
3. Set up the connection string in your project as follows:
   ```csharp
   string connectionString = "Data Source=server_name; Initial Catalog=your_db; Integrated Security=True;";
