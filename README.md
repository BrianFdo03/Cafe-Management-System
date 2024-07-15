# Cafe-Management-System

## Database

 - CafeManagementDatabase.mdf
 - CafeManagementDatabase_log.ldf

## Connection

  - Initialized inside a public class named DatabaseConnection.
  - Found in file "DatabaseConnection.cs".

## Register & Login User

  - After registering user the status of user will be set to **_Active_** by default.
  - If want to login with user then change status to **_Active_** from the database manually.
  - This feature was made so that it allows admin to approve or reject user types from the system.
