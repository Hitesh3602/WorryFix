# QUICKBOOK

QUICKBOOK is a comprehensive service booking website designed to streamline the process of finding and booking various services. Developed using Angular for the frontend, Spring Boot for the backend, and MSSQL for the database, QUICKBOOK offers a seamless and user-friendly experience for both customers and service providers.

## Features

- **Service Categorization**: Implemented a dynamic system allowing customers to browse and select services from various categories easily.
- **Viewing Previous Bookings**: Enhanced convenience by enabling customers to view details of their past bookings on a personal history page.
- **Customer Email Notifications**: Set up an automated email notification system that sends customers confirmation emails with booking details upon successful booking.
- **Worker Email Notifications**: Configured email notifications for service providers, informing them of new bookings with all necessary details for timely and accurate service delivery.

## Technologies Used

- **Frontend**: Angular
- **Backend**: Spring Boot
- **Database**: MSSQL

## Installation

### Prerequisites

- Node.js
- Angular CLI
- Java Development Kit (JDK)
- Apache Maven
- MSSQL Server

### Frontend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/quickbook.git
    cd quickbook/frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the Angular development server:
    ```bash
    ng serve
    ```

### Backend Setup

1. Navigate to the backend directory:
    ```bash
    cd quickbook/backend
    ```

2. Build the Spring Boot application:
    ```bash
    mvn clean install
    ```

3. Run the application:
    ```bash
    mvn spring-boot:run
    ```

### Database Setup

1. Ensure MSSQL Server is running and accessible.
2. Update the `application.properties` file in the backend with your MSSQL configuration.

## Usage

- Access the frontend application at `http://localhost:4200`.
- Use the provided interface to browse services, book services, and view previous bookings.
- Ensure email notifications are set up for both customers and workers to receive booking details.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
