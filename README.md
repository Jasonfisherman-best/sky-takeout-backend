# sky-takeout-backend
Sky Takeout
A full-featured takeout ordering platform backend system.
Overview
This is a complete takeout platform that includes admin dashboard and user ordering system, supporting business scenarios such as dish management, order processing, payment, shopping cart, address management, and data statistics.
Tech Stack
Backend: Spring Boot, Spring MVC, Spring Task
Database: MySQL, Redis
Persistence: MyBatis
Auth: JWT
Payment: WeChat Pay
Build: Maven
Core Features
Admin login & permission control (JWT)
Dish & category management
Shopping cart & order flow
Order payment & status management
User ordering & address management
Data statistics (revenue, orders, sales)
Automatic order cancellation via scheduled tasks
Modules
sky-common: common utilities & constants
sky-pojo: entity classes, DTO, VO
sky-server: core business services
