 Metro-Ticket-Generating-System-in-ServiceNow

 Metro Ticket Booking System

A **Metro Ticket Booking System** developed using **ServiceNow** to simplify and digitize the metro ticket booking process.

 Project Overview

The system allows users to:

- 🎫 Book metro tickets
- 🚉 Select starting and destination stations
- 👥 Enter number of passengers
- 🔄 Select journey type
- 💰 Calculate ticket fare
- 💳 Manage smart card details
- 💵 Select payment mode

Technologies Used

- **ServiceNow**
- **Service Catalog**
- **Catalog Items & Variables**
- **Custom Tables**
- **Catalog Client Scripts**
- **JavaScript**

Main Components

### Catalog Item
**Book a metro ticket**

The catalog item collects:

- Smart Card Number
- Smart Card Name
- Recharge Amount
- Starting From
- Going To
- Number of Passengers
- Type of Journey
- Fare Amount
- Payment Mode

 Custom Tables

**Metro Station's Details**
```text
u_metro_station_s_details
````

Stores metro station information.

**Metro Database**

```text
u_metro_database
```

Stores smart card and recharge information.

 Client Script

**FareCalculator**

* Type: `onChange`
* Variable: `type_of_journey`

The script retrieves the starting station, destination, and number of passengers to perform fare-related processing.

 Workflow


Open Service Catalog
        ↓
Book a Metro Ticket
        ↓
Enter Journey Details
        ↓
Select Journey Type
        ↓
Calculate Fare
        ↓
Select Payment Mode
        ↓
Submit Request

 Objectives

* Digitize metro ticket booking
* Simplify the booking process
* Automate fare-related calculations
* Manage station and smart card information

 Screenshots

Screenshots of the ServiceNow implementation are included in this repository. Future Enhancements

* Online payment integration
* QR-code ticket generation
* Booking history
* Ticket cancellation
* Email/SMS notifications
* Admin dashboard

 Project Details

**Project:** Metro Ticket Booking System
**Platform:** ServiceNow
**Domain:** Transportation
**Module:** Service Catalog


This version is **more suitable for GitHub** because it's concise while still explaining what your project does and the ServiceNow features you used.
```
