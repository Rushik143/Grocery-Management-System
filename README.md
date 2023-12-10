# Grocery Management System

This C++ program implements a simple Grocery Management System with features for billing, stock purchase, and stock data management. It includes an administrator (A) and staff (S) mode for different functionalities.

## Usage

Compile and run the program using a C++ compiler. You can choose the administrator or staff mode at the beginning.

### Administrator Mode

In administrator mode, you can perform the following tasks:

1. Billing:-Start a new bill, display all bills, or search for a specific bill.
2. Stock Purchase:- Purchase stock, display all stock purchase orders.
3. Stock Data:- Read, add, delete, modify, or search stock data.
4. Options:- Change staff details, change password.

### Staff Mode

In staff mode, you can perform the following tasks:

1. Billing:- Start a new bill, display all bills, or search for a specific bill.
2. Stock Data:- Read stock data or search for specific items.

## Classes

- bal:- Manages balance and profit calculations.
- admin:- Placeholder for administrator details (not implemented).
- staff:- Manages staff details and functionalities.
- grocery:- Represents grocery items with features for input, modification, display, and searching.
- purc:- Represents purchase orders with features for input, modification, and display.
- cust:- Represents customer bills with features for input, modification, and display.

## File Handling

The program uses file handling to store and retrieve data for grocery items, purchase orders, and customer bills.

## Compilation

bash
g++ gms.cpp -o gms
./a.out

### Note

Username and password are required to access the system.
The default administrator username is "admin" with the password "1234".
Staff details can be modified in administrator mode.

## Contribution
   - Rushikesh R. Patil
   
   
Feel free to contribute to the project by suggesting improvements or reporting issues.
