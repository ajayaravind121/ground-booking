
# Truf Booking System

## Project Overview
Truf Booking is a web-based application designed for streamlined turf reservation management. It supports user authentication, secure role-based access, automated email notifications for booking updates, and a user-friendly interface for managing bookings. The application is ideal for both administrators managing reservations and customers looking to book a slot.

## Features
1. **Secure Login System**  
   - Implemented using JSON Web Tokens (JWT) for secure authentication.
   - Role-based access for *admin* and *customer* users, ensuring authorized usage.

2. **Automated Email Notifications**  
   - Sends confirmation and cancellation emails to customers, improving communication and engagement.

3. **Booking Management System**  
   - Provides full CRUD operations for managing bookings.
   - Built with **Spring Boot** for robust backend services.
   - **Angular** is used for a responsive and dynamic frontend experience.

## Tech Stack
- **Frontend**: Angular
- **Backend**: Spring Boot
- **Authentication**: JSON Web Tokens (JWT)
- **Database**: MySQL (or any relational DBMS of choice)
- **Email Service**: JavaMailSender (for email automation)

## Setup Instructions
### Prerequisites
- **Node.js** and **npm** (for Angular)
- **Java** (for Spring Boot)
- **MySQL** (or any other compatible RDBMS)

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/truf-booking.git

### Backend Setup:
1. Navigate to the backend directory:
   ```bash
   cd truf-booking/backend
   ```
2. Update `application.properties` with your database credentials.
3. Run the backend server:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend Setup:
1. Navigate to the frontend directory:
   ```bash
   cd truf-booking/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the Angular app:
   ```bash
   ng serve
   ```
4. Access the application at `http://localhost:4200`.

## Usage

### User Login:
- Users can log in as either an admin or a customer.
- Admins have access to all bookings, while customers can view and manage their bookings.

### Booking Management:
- Admins can create, read, update, or delete bookings.
- Customers can book a slot, receive booking confirmation, and cancel bookings, with automated emails sent for both actions.

## Contributing
Please feel free to submit a pull request or report issues if you would like to contribute to this project.

## License
This project is licensed under the MIT License.

