# Software Requirements Specification (SRS)

# Vehicle Rental ERP System

Version: 1.0

Date: July 2026

Prepared By:
Lochana Ehelapitiya

---

# 1. Introduction

## 1.1 Purpose

The purpose of this document is to define the software requirements for the Vehicle Rental ERP System. The system aims to automate and integrate the daily operations of a vehicle rental company using Odoo ERP.

This document serves as the foundation for the design, development, testing, and maintenance of the system.

---

## 1.2 Scope

The Vehicle Rental ERP System is designed to manage the complete rental lifecycle of a vehicle rental business.

The system will support:

- Fleet Management
- Customer Management
- Vehicle Booking
- Rental Agreements
- Driver Management
- Vehicle Maintenance
- Payment Processing
- Invoice Generation
- Reports and Dashboards

The system will be developed using Odoo ERP and customized through custom modules.

---

## 1.3 Objectives

The main objectives are:

- Reduce manual paperwork
- Prevent duplicate bookings
- Improve fleet utilization
- Automate invoice generation
- Improve customer service
- Track maintenance schedules
- Generate management reports

---

# 2. Overall Description

## 2.1 Product Perspective

The Vehicle Rental ERP System is a customized ERP solution built on Odoo.

The system extends existing Odoo modules such as:

- Fleet
- Contacts
- Accounting
- HR
- Documents

Additional custom modules will be developed for rental-specific operations.

---

## 2.2 Product Functions

The system shall provide:

- Vehicle registration
- Vehicle availability management
- Customer registration
- Booking management
- Rental agreement generation
- Vehicle return processing
- Driver assignment
- Maintenance scheduling
- Invoice generation
- Dashboard reporting

---

## 2.3 User Classes

### Administrator

Responsibilities:

- Manage users
- Configure system
- Generate reports

### Booking Officer

Responsibilities:

- Manage reservations
- Confirm bookings
- Create rental agreements

### Fleet Manager

Responsibilities:

- Manage vehicles
- Schedule maintenance
- Update vehicle status

### Accountant

Responsibilities:

- Generate invoices
- Record payments
- Produce financial reports

### Driver

Responsibilities:

- View assigned rentals

### Customer

Responsibilities:

- Submit booking requests
- View rental history

---

# 3. Functional Requirements

## FR-01 Vehicle Management

The system shall allow administrators to:

- Register vehicles
- Update vehicle information
- Delete vehicles
- Upload vehicle images
- Track insurance expiry
- Track registration expiry
- View vehicle status

---

## FR-02 Customer Management

The system shall allow:

- Customer registration
- Customer profile management
- Driving license verification
- Rental history tracking

---

## FR-03 Booking Management

The system shall:

- Check vehicle availability
- Create bookings
- Modify bookings
- Cancel bookings
- Prevent double bookings

---

## FR-04 Rental Agreement

The system shall:

- Generate rental agreements
- Record pickup details
- Record return details

---

## FR-05 Driver Management

The system shall:

- Register drivers
- Assign drivers
- View driver schedules

---

## FR-06 Maintenance Management

The system shall:

- Schedule vehicle servicing
- Record maintenance history
- Notify upcoming maintenance

---

## FR-07 Payment Management

The system shall:

- Generate invoices
- Record payments
- Manage deposits
- Calculate rental charges

---

## FR-08 Reports

The system shall generate:

- Revenue reports
- Fleet utilization reports
- Booking reports
- Maintenance reports
- Customer reports

---

# 4. Non-Functional Requirements

## Performance

- Response time less than 3 seconds.

## Security

- Role-based access control.
- Secure authentication.
- Data backup support.

## Reliability

- 99% system availability.

## Scalability

- Support multiple branches.

## Usability

- User-friendly interface.
- Responsive design.

---

# 5. Assumptions

- Internet connection is available.
- PostgreSQL database is operational.
- Users receive system training.

---

# 6. Constraints

- Built using Odoo ERP.
- PostgreSQL as the database.
- Python for backend customization.

---

# 7. Future Enhancements

- Online payment gateway
- GPS tracking
- Mobile application
- AI-based demand forecasting
- QR code vehicle check-in/check-out


