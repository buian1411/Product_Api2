# Project Title

## Overview
This project is a simple product management application that consists of an API for handling product data and a client-side application for user interaction.

## Project Structure
The project is organized into two main directories: `api` and `client`.

### API
- **Controllers**: Contains the `ProductController.cs` which handles HTTP requests related to products.
- **Models**: Contains the `Product.cs` which defines the properties of a product.
- **Services**: Contains the `ProductService.cs` which includes business logic for managing products.
- **Program.cs**: The entry point of the application that sets up the web application and middleware.
- **appsettings.json**: Configuration settings for the application.

### Client
- **index.html**: The main HTML file for the client-side application.
- **scripts**: Contains `main.js` for handling user interactions and API communication.
- **styles**: Contains `style.css` for defining the layout and appearance of the application.

## Setup Instructions
1. Clone the repository to your local machine.
2. Navigate to the `api` directory and run the application using your preferred method (e.g., using .NET CLI).
3. Open the `client/index.html` file in a web browser to access the client-side application.

## Usage Guidelines
- Use the API endpoints defined in the `ProductController` to perform CRUD operations on products.
- The client-side application allows users to interact with the API and manage product data easily.

## License
This project is licensed under the MIT License.