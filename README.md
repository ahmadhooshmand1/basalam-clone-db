# Basalam Clone - Relational Database Design

A relational database schema for a multi-vendor marketplace inspired by Basalam, modeled with PostgreSQL and DBML.

## Database Entities
- **Users & Logistics:** `users`, `user_addresses`
- **Vendors & Products:** `booths`, `products`, `product_reviews`, `coupons`
- **Cart & Checkout:** `carts`, `cart_items` (supporting save-for-later)
- **Orders & Billing:** `orders`, `order_items`
- **Financial Ledger:** `wallets`, `wallet_transactions` (with idempotency support)

## Files
- `schema.sql`: PostgreSQL DDL script.
- `schema.dbml`: DBML code for dbdiagram.io modeling.
- `erd-diagram.pdf`: Entity-Relationship Diagram.
