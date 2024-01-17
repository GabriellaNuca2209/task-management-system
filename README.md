# Task management system

A system to track and manage software development tasks, including task assignment, progress tracking, and reporting.

---

## Tech stack
- Java 17
- Spring Boot 3.2.1
- PostgreSQL
- Hibernate
- Maven
- Lombok
- Swagger

## Helpers
Make sure to configure your database connection as follows:
```
# Database connection properties
spring.datasource.url=jdbc:postgresql://localhost:5432/YOUR_DATABASE
spring.datasource.username=USERNAME
spring.datasource.password=PASSWORD
spring.datasource.driver-class-name=org.postgresql.Driver

# JPA properties
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect

# Logging properties
logging.level.org.hibernate.SQL=DEBUG
logging.level.org.hibernate.type.descriptor.sql.BasicBinder=TRACE
```

## Team members

- [Gabriella Nuca](https://github.com/GabriellaNuca2209)     
- [Andrei Mircea Anghel](https://github.com/rhacp)
- [Cezar Nedelcu](https://github.com/CezarN88)
- [Cristian-Daniel Ionescu](https://github.com/Daniel7Ionescu)
