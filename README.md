# Spring Profiles Example
Example of using Spring Profiles with @Component annotated classes and configuration files, specifically application.yml

## Info
### Beans:
[ProductionMrBean](src/main/java/com/example/profile/demo/beans/ProductionMrBean.java)
<br />
[RowanAtkinson](src/main/java/com/example/profile/demo/beans/RowanAtkinson.java)

### Configuration:
[Configuration File](src/main/resources/application.yml)
<br />
[GIF Banner](src/main/resources/banner.gif)

## To Run
### Enables ProductionMrBean bean
Runs on port 7070.

```bash
mvn spring-boot:run -"Dspring.profiles.active=prod"
```

### Enables RowanAtkinson bean
Runs on port 6969.

```bash
mvn spring-boot:run -"Dspring.profiles.active=dev"
```