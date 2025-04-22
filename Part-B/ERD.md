# Entity-Relationship Diagram (ERD)

## Overview
The ERD below shows the entities in the system and their relationships.

### Entities:
1. **User**: Represents the system user.
   - Attributes: `user_id`, `name`, `email`, `password`
2. **Product**: Represents the product available for sale.
   - Attributes: `product_id`, `name`, `price`, `category`
3. **Order**: Represents the order placed by a user.
   - Attributes: `order_id`, `user_id`, `product_ids`, `total_price`

### Relationships:
- **User → Order**: A user can have multiple orders (One-to-many).
- **Order → Product**: An order can contain multiple products, and a product can appear in many orders (Many-to-many).

## ER Diagram:
![ERD Diagram](![Erd-Img](https://github.com/user-attachments/assets/d9067a0f-3af0-4cf1-bc99-16f4852c1ce9))

