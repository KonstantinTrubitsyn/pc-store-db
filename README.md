# Online Electronics Store DB

Relational PostgreSQL database for an online computer electronics shop.

## Contents

- `schema.sql`: Database schema (3NF, OLTP)
- `seed.sql`: Example data
- `olap_queries.sql`: Analytical (OLAP) queries
- `report/`: Screenshots, Power BI charts, and report sections

## Tables

1. `categories`
2. `brands`
3. `products`
4. `stock`
5. `hot_offers`
6. `users`
7. `orders`
8. `order_items`
9. `admins`

## Setup

1. Create PostgreSQL DB `electronics_store`
2. Run `schema.sql` to create tables
3. (Optional) Run `seed.sql` to populate data
