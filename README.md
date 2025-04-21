# 🛒 E-commerce Database Design

## 📌 Overview
This project is a group assignment focused on designing and building a relational database for an e-commerce platform. It includes a well-structured Entity-Relationship Diagram (ERD) and a complete SQL schema to implement the database using MySQL.

---

## 🎯 Objective
To master the art of database design through collaborative development of an e-commerce database that handles products, variations, attributes, categories, sizes, colors, and images.

---

## 🗂️ Tables Included

| Table Name            | Description |
|-----------------------|-------------|
| `brand`               | Stores brand-related data |
| `product_category`    | Classifies products into categories |
| `product`             | Stores general product details |
| `product_image`       | Stores product image URLs |
| `color`               | Manages available color options |
| `size_category`       | Groups sizes into categories |
| `size_option`         | Lists specific size options |
| `product_variation`   | Links a product to its variations (size, color) |
| `product_item`        | Represents purchasable items with SKU and price |
| `attribute_type`      | Defines attribute data types (e.g., text, number) |
| `attribute_category`  | Groups attributes into categories |
| `product_attribute`   | Stores specific product attributes (e.g., material, weight) |

---

## 📊 ERD Diagram

The Entity-Relationship Diagram (ERD) illustrates how the tables are structured and related to each other.

📎 *See `ERD.png` in the repository for the visual diagram.*

---

## 📦 Files Included

- `ecommerce.sql` – MySQL schema to create the database.
- `Ecommerce.png` – Visual ERD generated using [dbdiagram.io](https://dbdiagram.io) or similar.
- `README.md` – Documentation and project overview.

---

## 🤝 Group Collaboration

This project was built collaboratively by our peer group. We focused on:

- Defining entities and relationships clearly.
- Using foreign key constraints for data integrity.
- Applying normalization principles to avoid redundancy.
- Leveraging GitHub for version control and communication.

---

## 👨‍💻 How to Use

1. Clone the repository:
   ```bash
 
