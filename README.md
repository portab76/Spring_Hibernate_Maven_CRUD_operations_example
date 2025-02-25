## Example of Spring Hibernate Maven JPA CRUD application. 

### Versiones pom.xml
```
- Java: jdk 1.8
- Spring Framework: 4.3.30.RELEASE
- Spring Data JPA: 1.11.23.RELEASE
- Hibernate: 5.4.33.Final
- MySQL Connector: 5.1.25
- JSTL: 1.2
- Servlet API: 3.0.1
```

### Configurar la base de datos
Modificar el archivo `application.properties` 
```
CREATE TABLE shops (
	`id` int(11) NOT NULL AUTO_INCREMENT,
	`name` VARCHAR(255) NULL,
	`employees_number` INT(3) DEFAULT 0,
	PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci; 
```

### Ejecutar en:

- Apache Tomcat: 8.x, 9.x  - https://www.oracle.com/middleware/technologies/weblogic-server-installers-downloads.html
- Oracle WebLogic: 12.2.x - https://archive.apache.org/dist/tomcat/
...
