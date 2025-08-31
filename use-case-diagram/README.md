# 🎯 Airbnb Clone Use Case Diagram

This directory contains the Use Case Diagram for the Airbnb Clone backend project. The diagram visualizes how different types of users interact with the system, highlighting the key functionalities and system boundaries.

---

## 📘 Objective

The Use Case Diagram serves the following purposes:

- Illustrate how various actors (Guest, Host, Admin, Payment Gateway) interact with the system
- Define the core functionalities supported by the backend
- Clarify the system boundary and external services
- Support planning and documentation for development and testing

---

## 👥 Actors

- **Guest**: A user searching for and booking properties
- **Host**: A user listing properties for rental
- **Admin**: An administrator managing users, listings, and transactions
- **Payment Gateway**: An external service used to process payments securely

---

## 🧩 Primary Use Cases

### For Guest
- Register (Includes: Verify Email)
- Login
- Search Properties (Includes: Filter Results, View Property Details)
- Create Booking (Includes: Validate Availability; Extends: Apply Discount)
- Cancel Booking (Includes: Check Cancellation Policy)
- Process Payment (Includes: Select Payment Method)
- Leave Review (Extends: Rate Host)
- Receive Notifications (Includes: Booking Confirmation, Payment Status Updates)

### For Host
- Register (Includes: Verify Email)
- Login
- Add/Edit Property (Includes: Upload Images, Add Amenities)
- Track Booking Status (Includes: View Pending Bookings, Confirm/Reject Bookings)
- Handle Payout (Includes: Configure Payout Method)

### For Admin
- Monitor/Manage Users
- Monitor/Manage Listings
- Monitor/Manage Bookings
- Monitor/Manage Payments

### For Payment Gateway
- Process Payment (Includes: Validate Payment Method)
- Handle Payout (Includes: Issue Payment)

---

## 🖼️ Diagram

The use case diagram was created using Draw.io and exported as a PNG file.

📎 Diagram:  
![Airbnb Clone Use Case Diagram](use-case-diagram/airbnb-use-case.png)

---

## 🛠️ Tools Used

- **Diagram Tool**: Draw.io (https://draw.io)
- **Format**: PNG
- **Repository**: [alx-airbnb-project-documentation](https://github.com/your-username/alx-airbnb-project-documentation)

---

## 📬 Contact

For questions or contributions, reach out to:

- 📱 +254 791 561 098  
- 📧 omondidanish77@gmail.com
