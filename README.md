# Cafe Order Management System

## Overview

The Cafe Order Management System is a simple Java-based application to manage cafe orders. It allows the creation of orders for customers, adding items to those orders, displaying order details, and checking the order status.

## Project Structure

## Classes

### Item Class

The `Item` class represents a menu item in the cafe.

- **Member Variables:**
  - `private String name;`
  - `private double price;`

- **Constructor:**
  - `Item(String name, double price)`

- **Methods:**
  - `String getName()`
  - `double getPrice()`
  - `void setName(String name)`
  - `void setPrice(double price)`

### Order Class

The `Order` class represents a customer's order.

- **Member Variables:**
  - `public String name;`
  - `public boolean ready;`
  - `public ArrayList<Item> items;`

- **Constructors:**
  - `Order()`
  - `Order(String name)`

- **Methods:**
  - `void addItem(Item item)`
  - `String getStatusMessage()`
  - `void display()`
  - `double getOrderTotal()`

  ### Expected Output

The application will create five orders, add items to them, display the order details, and print the status messages.
