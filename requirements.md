# Backend Requirements for Airbnb Clone

## 1. User Authentication
- **API Endpoints**:  
  - POST `/register`: Register new users.  
  - POST `/login`: Authenticate users.
- **Input**: Email, password.  
- **Output**: JWT token.  
- **Validation**: Email format, password strength.

## 2. Property Management
- **API Endpoints**:  
  - POST `/properties`: Add a new property.  
  - PUT `/properties/:id`: Edit a property.
- **Validation**: Title, location, price.

## 3. Booking System
- **API Endpoints**:  
  - POST `/bookings`: Create booking.  
  - GET `/bookings/:id`: View booking status.
- **Validation**: Check date availability.
