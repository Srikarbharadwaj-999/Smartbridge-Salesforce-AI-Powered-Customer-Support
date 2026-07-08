<div align="center">

# AI-Driven Customer Support and Service Automation System

### Salesforce Service Cloud | Flows | Prompt Builder | Reports | Dashboards

*A Salesforce-based smart customer service automation solution designed for an Electronics and Gadgets business.*

![Salesforce](https://img.shields.io/badge/Salesforce-Service%20Cloud-00A1E0?style=for-the-badge\&logo=salesforce\&logoColor=white)
![Prompt Builder](https://img.shields.io/badge/Prompt-Builder-0176D3?style=for-the-badge)
![Flow](https://img.shields.io/badge/Record%20Triggered-Flows-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</div>

---

# Project Overview

The **AI-Driven Customer Support and Service Automation System** is built using **Salesforce Service Cloud** to simplify and automate customer support activities for an international Electronics and Gadgets company.

This project provides a centralized platform to manage customers, products, orders, and support cases. It improves service operations by using Salesforce features such as Flows, Queues, Validation Rules, Approval Processes, Reports, Dashboards, and AI-based case summaries through **Prompt Builder**.

---

# Key Features

### Customer Management

* Stores customer details
* Maintains contact information
* Tracks customer type
* Records country-based customer data

### Product Management

* Manages product catalog
* Organizes product categories
* Stores product pricing
* Maintains warranty information
* Tracks available stock quantity

### Order Management

* Handles order records
* Links orders with customers
* Connects products with orders
* Tracks order status
* Maintains total order amount

### Support Case Management

* Records customer issues
* Manages case priority
* Tracks case status
* Stores resolution details
* Generates AI-based case summaries

### Automation

* Record-Triggered Flows
* Queue-based case assignment
* Approval process automation
* Business validation rules

### AI Features

* Salesforce Prompt Builder integration
* AI-generated case summaries
* Intelligent assistance for support teams

### Analytics

* Salesforce Reports
* Interactive Dashboards
* Customer support insights

---

# System Architecture

```text
Customer
    │
    ▼
Order
    │
    ▼
Product
    │
    ▼
Support Case
    │
    ├── Validation Rules
    ├── Record-Triggered Flow
    ├── Queues
    ├── Approval Process
    └── Prompt Builder
```

---

# Data Model

## Customer

* Customer Name
* Email Address
* Phone Number
* Country
* Customer Type

## Product

* Product Name
* Product Category
* Price
* Warranty Expiry Date
* Stock Quantity

## Order

* Order Number
* Customer Lookup
* Product Lookup
* Order Date
* Order Status
* Total Amount

## Support Case

* Case Number
* Customer
* Product
* Order
* Issue Type
* Priority
* Status
* Description
* Resolution
* AI Summary

---

# Salesforce Automation

### Validation Rules

* Description is mandatory for Critical cases
* Product selection is required for Warranty-related cases
* Resolution details must be entered before closing a case

### Record-Triggered Flow

* Executes when a new support case is created
* Automates case-related business logic
* Updates records based on defined conditions

### Queues

* Damage Support Queue
* Warranty Support Queue
* Order Support Queue

### Approval Process

* Handles Critical support cases
* Routes cases through an automated approval workflow
* Ensures proper review before final action

---

# AI Integration

Salesforce **Prompt Builder** is used to create professional AI-generated summaries for customer support cases.

The AI summary includes:

* Case details
* Customer issue description
* Priority level
* Current case status

---

# Reports and Dashboard

### Reports

* Support Cases by Status
* Orders by Status
* Products by Category

### Dashboard

**Customer Support Dashboard**

The dashboard displays:

* Case status distribution
* Order status overview
* Product category distribution
* Key support performance insights

---

# Security

The application includes basic Salesforce security configuration such as:

* System Administrator Profile
* Object-Level Security
* Field-Level Security
* Queue Membership Access

---

# Repository Structure

```text
Smartbridge-Salesforce-AI-Powered-Customer-Support
│
├── 📄 README.md
├── 📁 Documentation
├── 📁 Salesforce-Setup
├── 📁 Screenshots
```

---

# Author

**M Srikar Bharadwaj**

</div>
