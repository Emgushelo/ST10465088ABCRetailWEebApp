# ST10465088ABCRetailWEebApp
# ABC Retail Storage Solution

## Project Overview
A comprehensive web application demonstrating Azure Storage Services integration for a retail order processing system. The application showcases four Azure Storage services working together to provide scalable, reliable, and cost-effective data management.

## Student Information
- **Student Number:** ST10465088
- **Module Code:** CLVV7112
- **Project:** Project 1 - Azure Storage Solution

## Live Application
- **URL:** https://st10465088abcretailwebapp-ffgwckgyhvd7gdhq.canadacentral-01.azurewebsites.net

## Technologies Used
- **Framework:** ASP.NET Core MVC (.NET 8.0)
- **Azure Services:**
  - Azure Table Storage (Customer & Product Data)
  - Azure Blob Storage (Product Images)
  - Azure Queue Storage (Order Processing)
  - Azure File Storage (System Logs)
- **Frontend:** Bootstrap 4, Font Awesome, jQuery
- **IDE:** Visual Studio 2022
- **Deployment:** Azure App Service

## Features Implemented

### 1. Azure Table Storage
- **Customers Table:** Store and manage customer profiles
  - Create, Read, Update, Delete operations
  - PartitionKey: "Customer"
  - Minimum 5 records stored
- **Products Table:** Store product information
  - Create, Read, Update, Delete operations
  - PartitionKey: "Product"
  - Minimum 4 records stored

### 2. Azure Blob Storage
- **Container:** productimages
- Store product images and multimedia
- Automatic URL generation for images
- Support for multiple image formats
- Minimum 4 images stored

### 3. Azure Queue Storage
- **Queue:** orderprocessing
- Process orders as queue messages
- Inventory management integration
- Message format includes order details
- Queue processing functionality
- Minimum 4 order messages stored

### 4. Azure File Storage
- **Share:** logs
- Store system log files
- Upload/view/delete log files
- Automatic log generation
- Minimum 4 log files stored

## Project Structure
