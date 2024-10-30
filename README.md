<h1 align="center" style="font-family: 'Poppins', sans-serif; font-size: 2.5em; font-weight: bold;">CRUD API Spring Boot - Order Management</h1>

<p align="center">
  <img src="https://skillicons.dev/icons?i=spring,java,postgres,maven" alt="Tech Stack Icons" />
</p>

### Project Overview

This project is a RESTful API for Order Management built using **Spring Boot**, utilizing **Maven** for dependency management, **Lombok** for reducing boilerplate code, and **PostgreSQL** as the database. It provides comprehensive endpoints for managing orders, menus, carts, and vouchers.

### Tech Stack & Dependencies
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white)
![Lombok](https://img.shields.io/badge/Lombok-red?style=flat-square)

### Setup & Installation

- **Clone the repository**
    ```bash
    git clone https://github.com/Mochrks/crud-springboot-api.git
    cd crud-springboot-api
    ```

- **Configure Database**
    - Update `application.properties` with your PostgreSQL credentials:
    ```properties
    spring.datasource.url=jdbc:postgresql://localhost:5432/your_database
    spring.datasource.username=your_username
    spring.datasource.password=your_password
    ```

- **Build the project**
    ```bash
    mvn clean install
    ```

- **Run the application**
    ```bash
    mvn spring-boot:run
    ```

### API Endpoints

#### Menu Management
- `GET /api/menu` - Get all menu items
- `GET /api/menu/{id}` - Get menu item by ID
- `POST /api/menu` - Create new menu item
- `PUT /api/menu/{id}` - Update menu item
- `DELETE /api/menu/{id}` - Delete menu item

#### Cart Management
- `GET /api/cart` - Get cart items
- `POST /api/cart` - Add item to cart
- `DELETE /api/cart` - Remove item from cart

#### Voucher Management
- `GET /api/voucher` - Get all vouchers
- `POST /api/voucher` - Create new voucher
- `PUT /api/voucher/{id}` - Update voucher
- `DELETE /api/voucher/{id}` - Delete voucher

## Connect with me:
[![GitHub](https://img.shields.io/badge/GitHub-333?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mochrks)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Gdvisuel)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/mochrks)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mochrks)
[![Behance](https://img.shields.io/badge/Behance-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://behance.net/mochrks)
[![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white)](https://dribbble.com/mochrks)
