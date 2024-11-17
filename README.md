# ProductCatalogService

## Overview
The **ProductCatalogService** is a core microservice in the E-Commerce platform responsible for managing the product catalog. It provides APIs to create, read, update, and delete products, as well as features like searching, sorting, filtering, and paging of products. This service is designed to handle high traffic, ensuring efficient product discovery and management.

## Key Features
- **CRUD Operations**: Manage products with Create, Read, Update, and Delete functionality.
- **Search**: Search products based on various attributes like name, category, and price.
- **Sorting & Filtering**: Sort and filter products by attributes like price, rating, and availability.
- **Paging**: Efficient pagination to handle large product listings.

## Architecture
- **Spring Boot**: The service is built using the Spring Boot framework for quick setup and easy development.
- **Spring Data JPA**: For database interaction, we use Spring Data JPA with MySQL for persistent storage.
- **Microservices Architecture**: This service is a part of a broader microservices-based ecosystem that includes other services like User Service, Order Service, and Payment Service.
- **RazorPay Integration**: While not directly related to product management, the service integrates seamlessly with other microservices that handle payments.
- **Redis Cache**: Product data, such as product details and search results, is cached to optimize response time.

## Installation

### Prerequisites
- Java 8 or higher
- Spring Boot 2.x
- MySQL Database (for persistence)
- Redis (for caching)

### Steps to Run the Service

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-org/ProductCatalogServiceProxy.git
