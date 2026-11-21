# Gelato Shop Management System

## Project Overview

The **Gelato Shop Management System** is a software engineering project focused on analyzing requirements and designing a management system for a gelato shop.

The project applies software engineering concepts to understand the shop's business operations and define a system that supports sales, order processing, inventory management, promotions, menu management, and business reporting.

The project was developed as part of the **ITDS262 – Software Engineering Lab** course at the Faculty of Information and Communication Technology, Mahidol University.

## Project Objectives

- Gather and analyze the system requirements.
- Identify system users, their roles, and responsibilities.
- Model system functions and data flows.
- Design user interface mock-ups for the proposed system.
- Prepare test cases to evaluate key system functions.

## System Users and External Services

The system identifies the following actors:

- **Customer:** Reviews ordered items and payment totals before completing payment.
- **Employee:** Handles sales operations, manages orders, processes payments, and issues receipts. Access to functions depends on the employee's role.
- **Manager:** Has access to management functions such as inventory, promotions, sales reports, and branch performance.
- **QR Payment Service API:** External service for processing QR code payments.
- **Credit Card Service API:** External service for processing credit card payments.

## Main System Features

### 1. Account Management

- Create employee accounts.
- Edit employee information, roles, assigned branches, and account status.
- Delete or deactivate employee accounts.
- Control system access based on user roles.

### 2. Order and Sales Management

- Display products, prices, and product availability.
- Create and manage customer orders.
- Customize gelato products by selecting containers, flavors, and toppings.
- Add, edit, or remove items in an order.
- Calculate product totals and discounts.
- View order details and order history.
- Cancel orders and update their statuses.

### 3. Member Management and Promotions

- Register new members using customer information such as name and phone number.
- Search for member information using a phone number.
- Apply relevant membership benefits and discounts.
- Add and remove promotions.
- Configure promotion details, discount types, values, and conditions.

### 4. Payment and Receipt Management

- Review order items, quantities, discounts, and total payment.
- Accept cash payments and calculate change.
- Support QR code payments.
- Support credit card payments through an external payment service.
- Record payment results and update order status.
- Generate receipts after successful payment.

### 5. Inventory Management

- View remaining ingredient and stock quantities.
- Add stock when new ingredients are received.
- Reduce stock when items are sold or stock is adjusted.
- Notify employees when ingredients reach the defined low-stock level.

### 6. Menu Management

- View and manage gelato menu items.
- Add new products with names, categories, and prices.
- Edit product information and stock details.
- Delete or deactivate menu items that are no longer available.

### 7. Management Dashboard and Reports

- View shop performance information.
- Review sales and order statistics.
- View membership and payment method information.
- Compare branch performance.
- Generate sales reports.

## Software Engineering Activities

The project covers the following analysis and design activities:

- Functional requirements analysis.
- Non-functional requirements definition.
- Actor and responsibility identification.
- Use Case Diagram.
- Use Case Narratives.
- Functional Decomposition Diagram (Structure Chart).
- Data Flow Diagram (DFD) Level 0, Level 1, and Level 2.
- User interface Mock-up Prototype.
- Test Case design and execution.

## Non-Functional Requirements

The proposed system includes the following quality and operational requirements:

- Display product information within 3 seconds.
- Calculate order totals and discounts within 2 seconds.
- Support at least 20 concurrent users.
- Maintain at least 99% availability during shop operating hours.
- Apply role-based access permissions for employees and managers.
- Display remaining stock quantities within 3 seconds.
- Preserve order, payment, and stock records after successful saving.
- Connect to QR Payment Service API and Credit Card Service API.
- Back up data at least once per day and support data recovery.
- Provide an easy-to-use interface that allows new employees to learn basic functions within 30 minutes.

## Prototype

The project includes a mock-up prototype demonstrating the proposed system interfaces and workflows.

Prototype link: [Gelato Shop Management System](https://my-gelato-shop.thanawat-23012550.workers.dev)

The prototype screens cover login, point of sale (POS), product customization, order management, member registration, promotions, payment, receipts, inventory, management dashboard, sales reports, menu management, and employee account management.

## Testing

Three test cases were documented and executed for key workflows:

| Test Case | Module | Result |
|---|---|---|
| TC-01 | Member Registration | Pass |
| TC-02 | Order Cancellation | Pass |
| TC-03 | Cash Payment and Receipt Issuing | Pass |

The test cases specify preconditions, test steps, test data, expected results, actual results, and postconditions.

## Project Information

- **Course:** ITDS262 – Software Engineering Lab
- **University:** Mahidol University
- **Faculty:** Faculty of Information and Communication Technology
- **Academic Year:** 2026
- **Project:** Section 2, Group 3
- **Project Type:** Software Requirements Analysis, System Design, UI Prototyping, and Testing


