# OData Exercises - Northwind API

## Project Structure
```
/odata-test
  ├── northwind_exercises.http
  ├── responses/
  └── README.md
```
## Exercises

### 1. Orders with Customer Details
- **Query**: See `northwind_exercises.http`
- **Response**: `responses/orders_with_customers.json`
- **Description**: Retrieve orders with their associated customer information.

### 2. Get the employees that report to manager “2”.
- **Query**: See `northwind_exercises.http`
- **Response**: `responses/employees_reports_to.json`
- **Description**: Retrieve employees that report to the manager 2 in this case.

### 3. Get the products that have stock (inventory).
- **Query**: See `northwind_exercises.http`
- **Response**: `responses/products_in_stock.json`
- **Description**: Retrieve Products that are in stock.

### 4. Get only the names and codes of products that are NOT in stock (inventory).
- **Query**: See `northwind_exercises.http`
- **Response**: `responses/products_without_stock.json`
- **Description**: Retrieve Products that are NOT in stock.

### 5. Get the 5 most expensive products
- **Query**: See `northwind_exercises.http`
- **Response**: `responses/products_most_expensive.json`
- **Description**: Retrieve 5 most expensive products.

### 6. Find the orders that were sent to “Germany”.
- **Query**: See `northwind_exercises.http`
- **Response**: `responses/order_germany.json`
- **Description**: Retrieve the orders that were sent to Germany.