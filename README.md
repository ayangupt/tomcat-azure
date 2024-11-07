# Tomcat Azure Deployment

This project demonstrates how to deploy an Apache Tomcat application.

## Prerequisites

- Java Development Kit (JDK) 17 or later
- Apache Tomcat 9 or later
- Maven is 3.6.0 or later

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/tomcat-azure.git
cd tomcat-azure
```

### Build the Project

```bash
mvn clean package cargo:deploy
```

Your app will be available at `http://localhost:8080/simple-tomcat-app`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Alternative Deployment Method

You can also deploy the application using the Cargo Maven plugin. This approach simplifies the deployment process.

```bash
mvn clean package cargo:deploy
```

Your app will be available at `http://localhost:8080/simple-tomcat-app`.