# RideEase-Cab-Booking-Management-System
RideEase is a Java-based cab booking management system that allows customers and drivers to sign up, log in, and manage cab booking operations through a console interface. Built using OOP concepts, layered architecture, repositories, and service-based modules for efficient authentication and booking management.
# RideEase – Cab Booking Management System

## Overview
RideEase is a Java-based console application designed to simulate a simple cab booking platform. The system allows customers and cab drivers to register, log in, and perform booking-related operations through a clean menu-driven interface.

## Features
- Customer Login & Signup
- Cab Driver Login & Signup
- Cab Booking Functionality
- Repository-Based Data Handling
- Service Layer Architecture
- Simple Console Interface

## Technologies Used
- Java
- Object-Oriented Programming (OOP)
- Collections Framework
- Scanner Class for User Input

## Project Structure
├── Main.java
├── services/
├── servicesAbstraction/
├── repo/

## Modules

### Authentication Module
Handles:
- User Registration
- User Login
- Role Selection

### Cab Booking Module
Handles:
- Booking a Cab
- Source and Destination Input

### Repository Module
Stores:
- Customer Data
- Cab Driver Data

## How It Works
1. User selects a role:
   - Customer
   - Cab Driver

2. User chooses:
   - Login
   - Signup

3. Customer can:
   - Book a Cab

4. System processes booking using service classes.

## Sample Flow
Choose a role
1. Customer
2. CabDriver

Choose the option
1. Login
2. Signup

Enter UserName
Enter Password

Choose an option
1. Book a cab

Enter Source
Enter Destination

## Concepts Used
- Interfaces
- Abstraction
- Encapsulation
- Layered Architecture
- Service-Repository Pattern

## Future Enhancements
- Fare Calculation
- Cab Availability Tracking
- GPS Integration
- Database Connectivity (MySQL)
- GUI/Web Application
- Payment Gateway Integration

## Author
Developed as a Java Mini Project for learning service-based application architecture and cab booking workflow.
