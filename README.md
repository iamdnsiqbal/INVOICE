# 🧾 Invoice Management System – Oracle APEX

A professional Invoice Management Application built using **Oracle APEX**, **Oracle SQL**, and **PL/SQL** to manage invoice creation, reporting, and printing.

---

## 📌 Overview

This application enables users to:

- Create and store invoices
- View invoice reports
- Print invoice details
- Maintain auto-generated invoice IDs using database trigger
- Apply validation and business logic using PL/SQL
- Generate invoice output in PDF format using BI Publisher (RTF Template)
- Interact with invoice data using an integrated AI Chat Agent

---

## 🤖 AI Chat Agent Integration

The application includes an AI-powered Chat Agent capable of answering real-time queries related to:

- Total number of invoices
- Invoice amount summary
- Supplier-wise invoice details
- Buyer-wise transaction history
- Product-wise sales and GST details
- Overall invoice analytics

The AI Chat enables conversational access to structured invoice data, transforming the system into an intelligent financial management platform.

---

## 🖨️ PDF Invoice Generation (BI Publisher)

When a user creates an invoice, the system generates a **print-ready PDF invoice** using:

- **Oracle BI Publisher**
- **RTF Invoice Template**
- Dynamic XML Data Source
- Structured invoice layout formatting

This ensures:

- Professional invoice design
- Standardized PDF output
- Accurate tax and total calculations
- Enterprise-ready reporting format

---

## 🏗️ Tech Stack

- Oracle APEX
- Oracle Database
- SQL
- PL/SQL
- Oracle BI Publisher (RTF Template)
- AI Chat Integration
- HTML & CSS (UI Customization)

---

## 🗂️ Database Components

- **USER_INVOICE Table**
- **SUPPLIER_DETAILS Table**
- **BUYER_DETAILS Table**
- **BANK_DETAILS Table**
- **OTHER_DETAILS Table**
- **PRODUCT_DETAILS_HEADER Table**
- **PRODUCT_DETAILS_LINE Table**
- **Triggers for GST and Total Price Calculation**
- **AUTH_INV Function for Authentication**

---

## ✨ Key Features

- Professional UI with custom CSS
- Form-based invoice entry
- Dynamic invoice report page
- Print-ready invoice layout
- Automated GST & total calculation via triggers
- Secure login authentication
- AI-powered conversational invoice insights
- BI Publisher based PDF invoice generation
- Structured and scalable database design

---

## 🚀 How to Use

1. Run `Invoice.sql` to create database objects.
2. Configure triggers and authentication function.
3. Import the APEX application.
4. Configure BI Publisher RTF template for PDF output.
5. Execute and manage invoices through the UI.

---

## 👨‍💻 Developer

**Md Danish Iqbal**  
Oracle APEX | Techno-Functional Consultant  

---


