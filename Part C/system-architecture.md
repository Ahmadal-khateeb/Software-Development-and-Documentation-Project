## 4.1 System Architecture – MVC Design for AI-Powered E-commerce Platform

The system is built using the **Model-View-Controller (MVC)** architecture, which separates the application into three interconnected components. This design promotes organized code, scalability, and maintainability.

---

###  Components

#### 1. Model (Data Layer)
- Responsible for data handling and business logic.
- Communicates directly with the **MySQL** database.
- Includes core entities:
  - `User`
  - `Product`
  - `Order`
  - `Inventory`
- Performs:
  - CRUD operations
  - Data validation

#### 2. View (Presentation Layer)
- Built using **HTML**, **CSS**, and **JavaScript**.
- Handles all user interface elements.
- Displays:
  - Product Listings
  - Personalized Recommendations
  - Shopping Cart
  - AI Chatbot Interface

#### 3. Controller (Application Logic)
- Acts as a bridge between **Model** and **View**.
- Handles:
  - HTTP Requests
  - User Inputs
  - Routing
- Calls appropriate model functions and updates the view.

#### 4. AI Layer (Intelligent Services)
- Implemented using **TensorFlow.js** and custom **Machine Learning** models.
- Works with the controller to enable:
  - AI-powered product search (image & text-based)
  - Personalized product recommendations
  - Inventory demand predictions
  - Fraud detection mechanisms
  - Real-time chatbot assistance

---

###  Data Flow
![Use Case](https://github.com/user-attachments/assets/4db57ff5-7d47-422a-8419-34e64a7ae3f4)



