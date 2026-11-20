# PrestaShop Deployment on AWS

## Project Overview
This project documents my assessment deployment of PrestaShop, an open-source e-commerce application, on Amazon Web Services (AWS).

## Technologies Used
- AWS EC2
- Ubuntu Linux
- Apache Web Server
- PHP
- Amazon RDS MySQL
- PrestaShop

## AWS Architecture

The PrestaShop application was deployed using AWS cloud infrastructure.

### Architecture Components

- **Amazon EC2:** Hosted the Ubuntu Linux server.
- **Apache:** Served the PrestaShop web application.
- **PHP:** Provided the application runtime.
- **Amazon RDS (MySQL):** Provided the database for the application.
- **AWS Security Groups:** Controlled network access to the infrastructure.

### How the Components Work Together

1. A user accesses the PrestaShop storefront through the EC2 instance's public IP address.
2. Apache receives the HTTP request and serves the PHP-based PrestaShop application.
3. PrestaShop communicates with the MySQL database hosted on Amazon RDS.
4. Amazon RDS stores and retrieves application data.
5. The application returns the requested page to the user.

### Architecture Flow

User Browser
    |
    v
Amazon EC2 (Ubuntu Linux)
    |
    v
Apache + PHP + PrestaShop
    |
    v
Amazon RDS (MySQL)

## Deployment Process
1. Provisioned an Ubuntu EC2 instance.
2. Configured the Apache web server and PHP environment.
3. Configured a MySQL database using Amazon RDS.
4. Installed and configured PrestaShop.
5. Tested access to the storefront and administration interface.

## Security Considerations
- Restricted access using AWS security groups.
- Configured database connectivity for the application.
- Protected the administrative interface.

## Challenges and Learning
This project strengthened my understanding of cloud infrastructure, Linux server administration, application deployment, database connectivity, and troubleshooting.

## Project Evidence
The screenshots below document the PrestaShop application deployment on AWS, including the public storefront, administration dashboard, EC2 instance, Amazon RDS database, and MySQL connectivity verification.

## Author
Cloud Engineering Portfolio Project
## Project Screenshots

### 1. PrestaShop Storefront
![PrestaShop Storefront](screenshots/01_PrestaShop_Public_Storefront.png)

### 2. PrestaShop Admin Dashboard
![PrestaShop Admin Dashboard](screenshots/02_PrestaShop_Admin_Dashboard.png)

### 3. AWS EC2 Instance
![AWS EC2 Instance](screenshots/03_EC2_Running_Public_IP.png)

### 4. Amazon RDS Database
![Amazon RDS Database](screenshots/04_RDS_Available.png)

### 5. MySQL Database Connectivity
![MySQL RDS Connection](screenshots/05_Terminal_MySQL_RDS_Connected.png)
