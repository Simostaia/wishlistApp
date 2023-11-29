# WishlistApp - A Social Wishlist Network

**Developers:**
- Simone Staiano (M63001037)
- Luca Vivenzo (M63001072)

## Project Overview

Welcome to WishlistApp, a web application created as part of our university course on Software Architecture Design. This project showcases the application of software architecture principles to build a social network that simplifies the process of choosing and sharing presents among friends.

### Key Features

- **User Management:** Create an account, log in, and manage your user profile.
- **Friendships:** Add and manage friends within the network.
- **Wishlists:** Create and manage wishlists for various occasions.
- **Event Creation:** Plan events and attach wishlists to them.
- **Invitations:** Invite friends to events and share wishlists.
- **Security:** Implements Spring Boot Security with JWT token-based authentication.
- **Database:** Uses PostgreSQL to store user and application data.

## Table of Contents

- [Getting Started](#getting-started)
- [Architecture Overview](#architecture-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)

## Getting Started

Get started with WishlistApp in just a few simple steps:

1. **Sign Up:** Create an account on WishlistApp.
2. **Add Friends:** Connect with your friends on the platform.
3. **Create Wishlists:** Start creating your wishlists for different occasions.
4. **Plan Events:** Organize events and attach wishlists to them.
5. **Invite Friends:** Invite your friends to events and share your wishlists.

## Architecture Overview

WishlistApp follows a client-server architecture. The client-side, responsible for the web interface, is developed using Bootstrap, while the server-side logic is powered by the Spring Boot framework. The application adheres to RESTful API design.

The PostgreSQL database stores user data, wishlists, events, and more. Configure the database connection in the `application.properties` file.

### Authentication and Security

WishlistApp ensures data security using Spring Boot Security with JWT token-based authentication. Users must authenticate to access protected resources. Customize security settings in your Spring Boot application's configuration.

## Installation

To run WishlistApp locally, follow these installation steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/lucavivenzo/WishlistApp.git

2. **Navigate to the Project Directory:**
   ```bash
   cd WishlistApp/progetto
3. **Set up PostgreSQL:**
   Ensure you have PostgreSQL installed and create a database for WishlistApp. Update the **'application.properties'** with the database connection details.
4. **Build and Run the Spring Boot Application:**
   ```bash
   ./mvnw spring-boot:run
5. **Open the Website:**
   Open a web browser and visit http://localhost:8080 to access the WishlistApp.

### Usage

* Sign in or create an account.
* Add friends and create wishlists.
* Plan events and invite friends to them.
* Share your wishlists and choose the perfect presents together.

## Project Structure

* **'src/main/'** - Server-side source code.
* **'src/main/resources'** - Application properties and configurations.
* **'src/main/resources/static'** - Client-side web interface.

## Technologies Used

WishlistApp incorporates a range of technologies and frameworks, including:

* **Frontend:** HTML, Bootstrap, JavaScript
* **Backend:** Spring Boot, Java
* **Database:** PostgreSQL
* **Security:** Spring Boot Security with JWT token authentication
