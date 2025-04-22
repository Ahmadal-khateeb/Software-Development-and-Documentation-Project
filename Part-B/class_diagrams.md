# Class Diagrams

## Overview
The class diagram below shows the structure of the main classes in the system and their relationships.

### Class: `User`
- **Attributes**:
  - `user_id: int`
  - `name: string`
  - `email: string`
  - `password: string`
- **Methods**:
  - `register()`
  - `login()`
  - `updateProfile()`

### Class: `Product`
- **Attributes**:
  - `product_id: int`
  - `name: string`
  - `price: decimal`
  - `category: string`
- **Methods**:
  - `addProduct()`
  - `updateProduct()`
  - `deleteProduct()`

### Class: `Order`
- **Attributes**:
  - `order_id: int`
  - `user_id: int`
  - `product_ids: list[int]`
  - `total_price: decimal`
- **Methods**:
  - `placeOrder()`
  - `cancelOrder()`
  - `trackOrder()`

## Relationships:
- **User → Order**: One-to-many relationship (a user can place multiple orders).
- **Order → Product**: Many-to-many relationship (an order can contain multiple products).
