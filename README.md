# My Diary Application

# Overview

My Diary Application is a personal diary management tool that provides a secure and intuitive platform for users to manage their diary entries. Built with Spring Boot, MySQL, and JSP, this application allows users to securely log in, create, update, and delete their diary entries, all while maintaining a clean and user-friendly interface.

# Key Features

    User Authentication: Each user has a unique username and password to access their own diary. Authentication ensures that diary entries are kept private and secure.
    Diary Management: Users can create, update, and delete diary entries. Each entry includes a date and description, allowing users to keep detailed records of their thoughts and experiences.
   # User and Entry Database:
        Users Table: Contains user credentials (username and hashed password) for authentication purposes.
        Entries Table: Stores individual diary entries linked to users by user ID, including entry date and descriptive text.

# Technologies Used

     Spring Boot: Provides the backend framework for building and running the application.
     MySQL: Manages data storage and retrieval, handling user and diary entry data.
     JSP (JavaServer Pages): Delivers the front-end user interface, rendering HTML content and facilitating user interaction with the application.
