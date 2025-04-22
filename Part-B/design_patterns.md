# Design Patterns

## Singleton Pattern
- **Purpose**: The Singleton pattern ensures that a class has only one instance and provides a global point of access to that instance. This is useful for managing database connections or any global resource that needs to be shared across the application.
- **Implementation**: A `Database` class where only one instance is created and reused for all database operations.

## Factory Pattern
- **Purpose**: The Factory pattern allows the creation of objects without specifying the exact class of the object that will be created. It helps in managing complex object creation logic and enhances flexibility.
- **Implementation**: A `ProductFactory` class that creates different types of products (e.g., physical products, digital products) based on the input parameters.

## Observer Pattern
- **Purpose**: The Observer pattern is used to define a one-to-many dependency between objects, so when one object changes its state, all its dependents are notified automatically.
- **Implementation**: In our system, the `Order` class can notify the `User` about the status change of their order (e.g., shipped, delivered).
