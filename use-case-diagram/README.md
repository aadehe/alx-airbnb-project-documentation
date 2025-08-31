# Use Case Diagram

## Objective
The objective of this task was to design a **Use Case Diagram** that captures the interactions between the main actors and the backend system of the **Airbnb Clone Application**.
This diagram provides a **user-centric view** of the system’s functional requirements, ensuring clarity in how different users achieve their goals when interacting with the platform.  

## Actors
The primary actors in the system are:  

- **Guest**  
  A registered or prospective user who searches for properties, makes bookings, processes payments, communicates with hosts, and leaves reviews.  

- **Host**  
  A user who lists properties on the platform, manages availability, accepts or declines bookings, and interacts with guests through messaging.  

- **Admin**  
  An internal system manager responsible for monitoring user activity, managing property listings, handling disputes, and ensuring smooth system operations.  

- **Payment Gateway**  
  An external system (e.g., Stripe, PayPal) that securely processes payments for confirmed bookings.  

## Use Cases
The diagram highlights the following key **use cases**:  

### 1. **User Management**
- Register and Log In  
- Manage Profile (update account details, reset password)  

### 2. **Property Management**
- Add New Property Listing  
- Edit or Delete Listing  
- Manage Availability and Pricing  

### 3. **Search & Booking**
- Search & Filter Properties (by location, price, amenities, dates)  
- View Property Details  
- Book Property  
- Cancel Booking  
- View Booking History  

### 4. **Transactions**
- Make Secure Payment via Payment Gateway  
- Receive Booking Confirmation  
- Host Receives Payouts  

### 5. **Communication**
- Send and Receive Messages (Guest ↔ Host)  
- Receive Notifications (booking status, confirmations, cancellations)  

### 6. **Reviews**
- Leave Review and Rating after stay  
- View Property Reviews  

### 7. **Admin Functions**
- Manage Users (activate, suspend, or delete accounts)  
- Manage Listings (approve/reject inappropriate listings)  
- Moderate Reviews and Messages  
- View Reports and Analytics  

## Diagram
The **Use Case Diagram**, created with **Draw.io (diagrams.net)**, visually illustrates these interactions.  
It shows how each actor connects with the relevant use cases, giving a clear overview of the system’s behavior.  

![Airbnb Use Case Diagram](ALX%20Airbnb%20Use%20Case%20Diagram.png)

---

## Summary
This diagram serves as a blueprint for understanding the **scope of interactions** in the Airbnb Clone system.  
It ensures that the backend design aligns with real-world user needs, making it easier to guide development, testing, and future feature expansion.  
