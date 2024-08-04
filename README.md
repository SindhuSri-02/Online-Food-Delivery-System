# Online Food Delivery System
- Created an online food ordering and delivery system with restaurant listings, menus, order tracking, and payment integration.

## Tech Stack and Tools
- Java
- Maven
- Spring Boot Framework
- Spring Data JPA
- Hibernate
- MySQL
- Swagger-UI
- Lombok

## Modules
- Login Module
- Restaurant Module
- Customer Module
- Order Module
- Items Module
- Food Cart Module
- Bill Module

## ER- Diagram
![Er-diagram](https://user-images.githubusercontent.com/101379495/213903200-10b62ca4-cd7c-476c-9bc7-fdbb8e4de54b.png)




## Features
- Customer and Admin authentication & validation with session uniqueId.
- Admin Features:
 - Only registered admins with valid session id can do the CRUD operations like add/update/delete.
 - Admin can add restaurants and food items.
 - Admin can remove restaurants and items.
 
- Customer Features:
 - Customer can register themselves with the application.
 - Customer can login to get the valid session token(id).
 - View list of available items.
 - Add items to food cart, view cart details, placing the order, update and access other features.

