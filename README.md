# **User Management Screen UI Specification Document**
## **Overview**
This document outlines the requirements and specifications for the user management screen. It is intended for software developers who will create an interface that allows administrators to manage user accounts.
## **Requirements**
- The interface must be intuitive and easy to navigate.
- All text should be in English.
- The system must support CRUD operations (Create, Read, Update, Delete) for user accounts.
## **UI Components**
### Table View
- A table displaying existing users with the following columns:
  - **Username**
  - **Email**
  - **Enabled** status (Boolean)
- Each row represents a single user account.
- Include the following buttons:
  - **“+ New User”:** Opens a form to create a new user account.
  - **“Hide Disabled User”:** Toggles visibility of disabled users in the list.
### New User Form
- A form on the right side of the screen titled “New User” which includes the following fields:
  - **Username**
  - **Display Name**
  - **Email**
  - **Phone**
  - **User Roles** (dropdown menu): Allows selection of roles such as Guest or Super Admin from predefined options.
  - **Enabled** checkbox: To activate or deactivate an account upon creation.
### Buttons
- **“Save User”**: Located at the top right corner of the New User form; saves new or edited user information to the system.
## **Behavior**
### Table View
- Clicking **“+ New User”** opens an empty New User form ready for input.
- Clicking on any row allows editing of that particular user’s information.
