# System Architecture

## Overview
The system is designed using the **MVC (Model-View-Controller)** architecture to separate concerns and improve maintainability. It divides the system into three core components:
- **Model**: Handles data, business logic, and interactions with the database.
- **View**: The user interface that displays the data and handles user interactions.
- **Controller**: Acts as an intermediary between the Model and View, processing user inputs and updating the View accordingly.

## MVC Architecture Flow:
1. The **View** sends user input to the **Controller**.
2. The **Controller** processes the input, interacts with the **Model**, and updates the **View** with the result.
3. The **Model** handles all data-related operations and communicates with the database if necessary.

This separation makes the system more modular and easier to maintain.
