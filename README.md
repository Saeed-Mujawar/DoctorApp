<h1 align="center"> Doctor App </h1>

-   This is a Spring Boot application for managing a Doctor and patient Appointment and . It allows users to sign up, sign in, book and view appointment. The application has different levels of access based on user roles: admin, normal user.

>### Prerequisites

-   MySql
-   SpringBoot
-   Java
>### Data flow

In this project, we have four layers-

-   Controller - The controller layer handles the HTTP requests, translates the JSON parameter to object, and authenticates the request and transfer it to the business (service) layer. 
-   Service -The business layer handles all the business logic. It consists of service classes and uses services provided by data access layers.
-   Repository - This layer mainatains the mySQl-database thing on which CRUD operations are performed
-   Model - This layer consists basically the class level things- the various classes required for the project and these classes consists the attributes to be stored.

>### Models

>### Features
-   User Management:
    -   Sign up:Users can sign up using email
    -   Sign in: Users can sign in with their username and password.
    -   Role-based Access: Admin users have additional privileges, such as viewing all users, while normal users have restricted access.
-  Appointment Management:
    -   book Appointment: Patient can book appoinment by providing time and other details.
-  Doctor Management:
    -   See Appointment: Doctor can see their upcoming Appointments.

>### Project Summary

The Doctor App is a basic Spring Boot project designed to facilitate the management of doctor appointments. It provides a simple and user-friendly interface for users to schedule appointments with doctors. The application leverages the Spring Boot framework, which simplifies the development process and enhances efficiency. The Doctor App aims to streamline the appointment booking process and improve overall healthcare service delivery.
