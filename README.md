# IN226076602_API-TASK-4
# FastAPI Cart System – Assignment 1

## Internship Training – FastAPI Module

This project is part of the FastAPI internship training assignment.
The objective of this assignment is to build a simple **Shopping Cart API** using FastAPI and test multiple API endpoints such as adding items, viewing cart contents, updating quantities, removing items, and performing checkout.

---

## Technologies Used

* Python
* FastAPI
* Uvicorn
* Swagger UI (for API testing)

---

## Features Implemented

1. Add items to cart
2. View cart items and calculate total
3. Handle out-of-stock products
4. Update quantity of existing cart items
5. Remove items from cart
6. Checkout and generate orders
7. View order history

---

## API Endpoints

### Cart Endpoints

* **POST /cart/add** → Add item to cart
* **GET /cart** → View cart items
* **DELETE /cart/{product_id}** → Remove item from cart
* **POST /cart/checkout** → Checkout cart

### Order Endpoint

* **GET /orders** → View all orders

---

## Example Workflow

1. Add products to cart using `/cart/add`
2. View cart using `/cart`
3. Update item quantity automatically if the same product is added again
4. Remove items using `/cart/{product_id}`
5. Checkout cart using `/cart/checkout`
6. View placed orders using `/orders`

---

## Screenshots

The repository includes screenshots for each assignment task:

* Q1_Output.png
* Q2_Output.png
* Q3_Output.png
* Q4_Output.png
* Q5_Output.png
* Q6_Output.png

These screenshots demonstrate the successful execution of each API operation.

---

## Running the Project

Install dependencies:

pip install fastapi uvicorn

Run the server:

uvicorn main:app --reload

Open Swagger UI in browser:

http://127.0.0.1:8000/docs

---

## Author

Himanshu Singh
FastAPI Internship Assignment
