# Inventory-App-Android

CS 360 Mobile Architect and Programming
Southern New Hampshire University

Inventory App Android

Portfolio Artifact Overview

This repository contains the completed Android application developed during CS 360 Mobile Architect and Programming. The project demonstrates the full mobile development lifecycle, including UI design, database integration, runtime permission handling, testing, and launch planning. The submitted artifact includes the finalized app code design ZIP file from Project Three, which builds upon the UI foundation developed in Project Two.

This application reflects my ability to design and develop a fully functional mobile app using Android Studio and Java while applying user-centered design principles and development best practices.

App Requirements and Goals

The goal of this application was to develop a functional mobile inventory management system that allows users to securely log in and manage inventory items. The app was designed to address the need for a simple, reliable tool for tracking inventory quantities and receiving alerts when stock levels fall below a defined threshold.

User needs addressed by this application include:

Secure account creation and login

Persistent storage of inventory data

Ability to create, read, update, and delete inventory items

Clear and intuitive navigation

Optional SMS alerts when inventory levels are low

Continued functionality even if SMS permission is denied

The overall objective was to create a complete and stable mobile solution that integrates both front-end design and back-end functionality.

User Interface and User-Centered Design

The application includes several key screens that support user needs:

Login and account creation screen

Inventory display screen using a grid layout

Add item screen

Edit item screen

SMS notification settings screen

Each screen was intentionally designed with simplicity and clarity in mind. Navigation flows logically from login to inventory management, and actions are clearly labeled to reduce confusion. The use of consistent spacing, layout structure, and visual hierarchy helps users quickly understand how to interact with the application.

User-centered design was implemented by considering real-world user behavior. For example, the app handles permission denial gracefully, ensuring the application continues functioning even if SMS access is not granted. Additionally, input validation was implemented to prevent crashes and reduce user error. These decisions ensured the design was not only visually organized but also practical and resilient.

Development Approach and Coding Strategy

My approach to development followed a structured and incremental process. I first finalized the UI layout before implementing backend logic. Once the UI was stable, I integrated SQLite for persistent data storage and developed full CRUD functionality through a dedicated database helper class.

The development process was divided into manageable stages:

Database structure implementation

Login validation logic

CRUD operations for inventory

RecyclerView integration for data display

Runtime SMS permission handling

Conditional SMS alert functionality

Testing was performed after each major feature was added to ensure stability before moving forward. This incremental strategy reduced debugging time and improved code clarity.

The techniques used in this project, such as separating database logic into its own helper class and validating user input before database operations, are transferable to future mobile and software development projects. This structured development method improves maintainability and scalability.

Testing and Validation

Testing was conducted using the Android Emulator to ensure all features operated correctly. Functionality tested included:

Account creation and login validation

Database persistence after closing and reopening the app

Create, read, update, and delete operations

SMS permission granted and denied scenarios

Low inventory alert triggering

Testing permission handling was particularly important because the app was required to function correctly regardless of whether the user granted SMS access. This process revealed the importance of defensive programming and validating all possible user decisions.

Thorough testing ensured the application builds successfully, runs without crashes, and meets all functional requirements.

Innovation and Problem Solving

One of the primary challenges in this project was implementing SMS permission handling in a way that aligned with Android runtime permission requirements while ensuring the application remained stable if access was denied. Overcoming this challenge required researching Android permission best practices and implementing conditional logic that prevented crashes and unnecessary prompts.

Another challenge involved ensuring database persistence and properly refreshing the RecyclerView when updates occurred. Solving this required thoughtful lifecycle management and reloading data during activity resume events.

These problem-solving experiences strengthened my understanding of real-world application behavior and reinforced the importance of planning and testing.

Demonstration of Knowledge and Skills

The component of this project that most strongly demonstrates my technical ability is the integration of SQLite with full CRUD functionality alongside runtime permission handling. Successfully connecting front-end UI components with backend database logic while maintaining app stability reflects a strong understanding of Android architecture principles.

Additionally, implementing conditional SMS alerts based on inventory thresholds showcases my ability to apply logical decision-making within application flow. This project demonstrates my competency in mobile application design, database integration, user-centered thinking, and structured development practices.

Overview

This project represents the successful completion of a full mobile app development cycle. From initial UI design to final functional implementation and launch planning, the Inventory Management Application showcases my ability to develop a stable, user-focused Android application using modern development standards.

This artifact serves as a portfolio example of my growth in mobile architecture, database integration, permission management, and iterative development strategies. It reflects both technical competency and an understanding of the complete application lifecycle from planning through potential launch.
