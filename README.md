# Spring-MVC-small-Project-For-Test-pre-post-and-after

This repository contains a small Java Spring MVC application showcasing the usage of Pre-Handler, Post-Handler, and After Completion methods.

## Introduction

This project demonstrates the implementation of various handler methods in a Java Spring MVC application. These methods play a crucial role in intercepting and processing HTTP requests before they reach the controller (Pre-Handler), after the controller handles the request (Post-Handler), and once the request has been fully processed (After Completion).

## Features

- **Pre-Handler Method:** Intercepting HTTP requests before they are handled by the controller.
- **Post-Handler Method:** Executing logic after the controller has processed the request but before the response is sent.
- **After Completion Method:** Performing cleanup tasks after the request has been fully processed.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Prohit0152/Spring-MVC-small-Project-For-Test-pre-post-and-after
   ```

2. **Build the Project:**
   ```bash
   mvn clean install
   ```

3. **Run the Application:**
   ```bash
   mvn spring-boot:run
   ```

4. **Access the Application:**
   Open a web browser and go to `http://localhost:8080`.

## Usage

Once the application is running, you can test the functionality of the pre-handler, post-handler, and after completion methods by sending HTTP requests to the defined endpoints.

## Configuration

No additional configuration is required to run this project. However, feel free to explore the `application.properties` file for any customizations.

## Contributing

Contributions are welcome! If you'd like to enhance this project or report any issues, please feel free to submit a pull request or create an issue on the repository.

---
