Purpose and Scope

Purpose:
The purpose of the Tour Management System is to provide a simple system for managing users, tour packages, bookings, customers, travelers, payments, and administrative activities.

In Scope

User registration and login.
Tour package listing and search.
Tour booking and cancellation.
Customer and traveler management.
Payment and booking status tracking.
Admin management of tours, bookings, and customers.

Out of Scope

Online travel agency or third-party service integration.
Advanced payment gateway integration.
Mobile application.
Real-time GPS or tour tracking.
Automated travel recommendations.
Functional Requirements
FR-01: The system shall allow users to register and log in.
FR-02: The system shall allow users to view and search available tour packages.
FR-03: The system shall allow users to book and cancel tour packages.
FR-04: The system shall allow customer and traveler information to be added, viewed, and managed.
FR-05: The system shall record payments and display the status of each booking.
FR-06: The system shall allow administrators to manage tours, bookings, and customer information.
Non-Functional Requirements
NFR-01: The system shall display normal user-requested pages or results within 3 seconds under normal local usage.
NFR-02: The system shall require valid login credentials before allowing access to user account functions.
NFR-03: The system shall provide interfaces that allow a new user to complete registration or booking within 5 minutes without assistance.
NFR-04: The system shall successfully process at least 95% of valid operations without application errors during normal use.
NFR-05: The system shall prevent unauthorized users from accessing administrator functions with 100% role-based access enforcement.
NFR-06: The system shall maintain SQLite data correctly across at least 100 consecutive create, update, and delete operations.
Assumptions
Users have basic knowledge of using a computer and web/application interfaces.
Tour package information is entered and maintained by the administrator.
Payment information is entered manually or recorded within the system.
The system will be used by a limited number of users suitable for a college project.
Python and SQLite are available on the system where the application is deployed.
Constraints
The system shall be developed using Python.
SQLite shall be used as the database.
The project is intended for a small-scale college project.
Development time and resources are limited to a few weeks.
The system shall not depend on advanced external services or third-party integrations.