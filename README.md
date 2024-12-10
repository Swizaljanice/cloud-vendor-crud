# Cloud Vendor API

A simple Spring Boot application for managing cloud vendor details. This application demonstrates basic RESTful API operations like Create, Read, Update, and Delete (CRUD).

## Features
- **GET** `/cloudvendor/{vendorId}`: Fetch details of a cloud vendor by their ID.
- **POST** `/cloudvendor`: Create a new cloud vendor.
- **PUT** `/cloudvendor`: Update an existing cloud vendor.
- **DELETE** `/cloudvendor/{vendorId}`: Delete a cloud vendor by their ID.

## Technologies Used
- **Spring Boot**: Framework for building Java-based applications.
- **Maven**: Dependency management and build automation tool.
- **Java**: Programming language.

## Project Structure
rest-demo/ ├── src/ │ ├── main/ │ │ ├── java/com/swizal/rest_demo/ │ │ │ ├── controller/CloudVendorAPIService.java # REST API controller │ │ │ └── model/CloudVendor.java # CloudVendor model class │ │ └── resources/application.properties # Application properties ├── pom.xml # Maven configuration ├── mvnw, mvnw.cmd # Maven wrapper scripts ├── .mvn/ # Maven wrapper files └── README.md # Documentation file
