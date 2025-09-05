# E-Cart Java Swing Application
Project Overview
A complete desktop e-commerce application built with Java Swing that provides a graphical user interface for online shopping with full cart management and checkout functionality.

Functionalities
Login & Registration System

Registration Requirements:

Email validation with special character "@"

Password minimum 8 characters

Phone number must be exactly 11 digits

Secure login with registered credentials


Product Catalogue
Browse available products

Add/remove items from cart

Product display with details


Shopping Cart Management
Quantity adjustment with +/- buttons

Real-time cart updates

Item management (add/remove)


Billing System
Automatic invoice generation

Price calculation with quantities

Order summary display


Checkout Process
Order confirmation

COD (Cash on Delivery) payment method

Phone number validation (11 digits)


Logout System
Secure session termination

Return to login screen


Project Structure
Class 1: eCartApplication
Main application class containing:

Login/registration interface

Main application window

Navigation between panels

User authentication logic

Class 2: CartManager
Cart management class containing:

Shopping cart operations

Quantity adjustment logic

Price calculations

Invoice generation


Setup Instructions
Create a new Java project in your IDE

Create first class named: eCartApplication

Create second class named: CartManager

Copy the provided code into respective classes

Run the eCartApplication class to start the application


Application Flow
Launch Application → Starts with login/registration screen

Register/Login → Create account or login with existing credentials

Browse Catalogue → View products and add to cart

Manage Cart → Adjust quantities and review items

Checkout → Complete order with COD payment

Invoice Generation → Receive order confirmation

Logout → End session and return to login screen


Validation Rules
Email: Must contain "@" symbol

Password: Minimum 8 characters

Phone: Exactly 11 digits

Cart: Quantity must be ≥ 1

Checkout: All fields mandatory


UI Components
Swing frames and panels

Buttons with action listeners

Text fields with input validation

Tables for product display

Dialog boxes for messages

This application provides a complete e-commerce experience with focus on user-friendly interface and robust functionality using Java Swing components.
