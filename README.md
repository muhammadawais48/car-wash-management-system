# Car Wash Management System

**BS Computer Science Final Year Project (2023)**  
Government College University Faisalabad (GCUF)

A PHP and MySQL web application for presenting car-wash services, accepting appointment requests, and supporting administrative management of bookings, washing points, enquiries and website content.

**Repository:** https://github.com/muhammadawais48/car-wash-management-system

## Project overview

The application brings customer-facing car-wash service information and administrative operations into one web-based system. Customers can explore washing plans and submit appointments or enquiries. Administrators can manage bookings, washing points, website pages and customer enquiries.

## Features

### Customer-facing pages
- Home, About Us, Washing Plans, Washing Points and Contact Us
- Premium washing services
- Appointment booking form
- Customer enquiry form

### Administration
- Admin login and password-change page
- Dashboard
- Add and manage washing points
- Add, view, update and delete booking records
- Customer enquiry management
- Website page management
- Printable reports

## Technology stack

| Layer | Technologies |
|---|---|
| Backend | PHP |
| Database | MySQL |
| Frontend | HTML, CSS, Bootstrap, JavaScript |
| Local environment | XAMPP (Apache and MySQL) |

## Application workflow

1. A visitor views services, plans and washing-point information.
2. The visitor submits an appointment request or an enquiry.
3. An administrator signs in to review and manage bookings and enquiries.
4. Administrators maintain washing-point information and site content.

## Running locally

**Prerequisites:** A local PHP/MySQL environment such as XAMPP, and the project's compatible database SQL export.

1. Install XAMPP and start Apache and MySQL.
2. Copy the repository folder into XAMPP's `htdocs` directory.
3. Create the database in phpMyAdmin and import the project's SQL export **if available**.
4. Review the database connection settings in `config.php` and use local development credentials.
5. Open `http://localhost/car-wash-management-system/` (adjust the URL if the folder name differs).
6. Test the customer booking and admin flows with non-sensitive sample data.

**Database note:** The presence and completeness of an importable SQL export have not been verified. If it is missing, add a sanitized schema/data export before claiming the setup is reproducible. Never commit live credentials or customer information.

## Screenshots

Real application screenshots can be added to the `screenshots/` folder after running the project locally. Recommended captures: home page, booking form, admin dashboard, and washing-point management. Do not use mockups as evidence of a running application.

## Project team

- Muhammad Awais
- Muhammad Ahmar Saleem

**Supervisor:** M. Sohaib Yousaf  
**Institution:** Government College University Faisalabad  
**Year:** 2023

This was a group final-year project. Individual responsibilities should be described separately where needed and only when verified.

## Scope and verification

This README documents features and technologies listed in the repository. The application has **not** been executed or security-tested as part of this documentation update. Deployment readiness, database integrity and authentication security require testing in a local environment.

## Related work

[Car Wash Data Analysis (Python and SQL)](https://github.com/muhammadawais48/car-wash-data-analysis) — a separate data analysis project.
