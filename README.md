# Investigative Commission System for Gender-Based Violence
## Università degli Studi di Salerno - Department of Information Engineering and Electrical and Applied Mathematics

This system is designed to manage an investigative commission on gender-based violence. It was developed as part of the 2021/2022 Information Systems course.

## System Description
The system oversees the creation of an investigative commission, its operational dynamics, and the generation of a report based on investigations.

## Architecture
The system is based on distributed microservices, implemented across four subsystems: Client, Server, Data Storage, and External Services, using an MVC pattern.

### Client Subsystem
Developed with JavaFX and Scene Builder, this subsystem handles the user interface, including dashboard, login, messaging, and report editing modules.

### Server Subsystem
This subsystem manages microservices, real-time messaging, and notifications. It is developed with NodeJS, and Spring boot is used for managing micro-services.

### Data Storage Subsystem
This subsystem uses MongoDB for the database, housed in a Docker container, ensuring scalability and traceability of data.

### External Services Subsystem
This subsystem integrates Google Calendar, Google Docs, and Gmail for various functionalities, and uses RESTful APIs for server communication.

### View Rendering
The dynamic and improved graphical interface is achieved using CSS3 and JavaScript. WebSockets are used for the exchange of messages and notifications, and OkHttp is used for communication between the controller and APIs.

For more details about the system, please refer to the full project report.
