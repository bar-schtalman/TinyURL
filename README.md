# TinyURL Project

## Overview
This project is a URL shortening service built using Java Spring Boot (version 11). It leverages Redis, MongoDB, and Cassandra to provide efficient and scalable URL shortening, user management, and click tracking functionalities.

## Features
- **URL Shortening**: Uses an appropriate algorithm to shorten long URLs.
- **User Management**: Stores user information in MongoDB.
- **Click Tracking**: Records click details (including time) for each shortened URL in Cassandra.

## Tech Stack
- **Java Spring Boot (version 11)**
- **Redis**: For saving shortened URLs.
- **MongoDB**: For managing user data.
- **Cassandra**: For tracking clicks on URLs.
- **Swagger**: For API documentation.

## Usage
- **Shorten a URL**: Send a POST request to `/api/shorten` with the long URL.
- **Retrieve original URL**: Send a GET request to `/api/{shortUrl}`.
- **User Management**: Endpoints for user registration and management.
- **Click Tracking**: Access click statistics for each shortened URL.
- **API Documentation**: Access the Swagger UI at   [Swagger UI](https://bars-tinyurl.runmydocker-app.com/swagger-ui.html#/app-controller)` for detailed API documentation.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
