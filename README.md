# eCommerce
# E-commerce Website Project

## Overview

This project is a full-stack e-commerce website developed using Java, JSP (JavaServer Pages), Servlets, and JDBC (Java Database Connectivity). The website provides a platform for users to browse and purchase products, while also offering administrative functionalities for managing products and user information.

## Features

- **User Registration and Authentication:** Allows new users to register and existing users to log in securely.
- **Product Browsing:** Users can view a list of products, search for specific items, and filter products by categories.
- **Shopping Cart:** Users can add products to their shopping cart, update quantities, and remove items.
- **Order Management:** Users can place orders, view order history, and track the status of their orders.
- **Admin Panel:** Admins can manage products, categories, and user information through a dedicated admin interface.
- **Database Integration:** Utilizes JDBC for connecting to and interacting with a relational database to store user, product, and order information.

## Technologies Used

- **Frontend:**
  - HTML, CSS, JavaScript for building the user interface.
  - JSP for dynamic content rendering.

- **Backend:**
  - Java Servlets for handling HTTP requests and responses.
  - JDBC for database operations.
  - MySQL (or any preferred relational database) for data storage.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed.
- Apache Tomcat or any other Java EE compatible web server.
- MySQL or any preferred relational database.
- IDE (e.g., IntelliJ IDEA, Eclipse) for Java development.

### Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/e-commerce-website.git
   ```
2. **Import the Project:**
   - Open your IDE and import the cloned project as a Maven or Gradle project.
3. **Configure the Database:**
   - Create a new database in your MySQL server.
   - Execute the provided SQL script (`database.sql`) to create the necessary tables.
   - Update the `db.properties` file with your database connection details.
4. **Deploy to Server:**
   - Build the project using your IDE or Maven/Gradle commands.
   - Deploy the generated WAR file to your Apache Tomcat server.
5. **Run the Application:**
   - Start your Tomcat server and navigate to `http://localhost:8080/e-commerce-website` to access the website.

## Usage

- **User Operations:**
  - Register a new account or log in with existing credentials.
  - Browse products and add desired items to the shopping cart.
  - Proceed to checkout to place an order.

- **Admin Operations:**
  - Log in to the admin panel.
  - Manage products by adding, updating, or deleting items.
  - View and manage user information and order details.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request to the main branch of the original repository.

## Contact

If you have any questions or suggestions, feel free to reach out to me at (mailto:dudipallishashi@gamil.com).

---

Thank you for using this e-commerce website project! Happy coding!
