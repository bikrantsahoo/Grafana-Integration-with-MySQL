# Grafana Integration with MySQL DevOps Project

## Description
This project demonstrates the integration of Grafana with a MySQL database to visualize and monitor data. It provides a set of scripts and configurations to automate the deployment and configuration of the Grafana instance, along with connecting it to the MySQL database.

## Features
- Grafana installation and configuration
- Integration with MySQL database
- Pre-configured dashboards for MySQL monitoring
- Automated data source setup
- Dashboard provisioning using JSON templates
- Continuous Integration/Continuous Deployment (CI/CD) with Jenkins

## Prerequisites
- Docker
- Docker Compose
- MySQL Server on AWS premises

## Getting Started
To get started with this project, follow the instructions below:

### 1. Clone the Repository
git clone https://github.com/yourusername/grafana-mysql-integration.git


### 2. Configuration
- Open `docker-compose.yml` and adjust the environment variables for the MySQL database connection (e.g., username, password, host, port).
- Optionally, modify or add additional dashboards in the `dashboards` folder.

### 3. Start the Stack

### 4. Access Grafana
- Open a web browser and visit `http://localhost:3000`.
- Log in with the default credentials (admin/admin).

### 5. Configure MySQL Data Source
- Navigate to "Configuration" > "Data Sources" in the Grafana UI.
- Click on "Add data source" and select "MySQL".
- Enter the necessary details for your MySQL database connection (e.g., host, port, username, password).
- Test the connection and save the data source.

### 6. Import Dashboards
- Navigate to "Create" > "Import" in the Grafana UI.
- Browse the `dashboards` folder and import the desired JSON dashboard templates.
- Adjust any additional settings as needed and save the dashboards.

## Usage
- Access Grafana UI: `http://localhost:3000`
- Explore the pre-configured dashboards for MySQL monitoring and analytics.
- Customize or create new dashboards based on your specific requirements.
- Configure alerts, notifications, and other Grafana features as desired.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please submit a pull request.
