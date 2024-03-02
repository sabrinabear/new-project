**Translation:**
# Shopping System
=====================
[![Build Status](https://travis-ci.org/vito16/shop.svg?branch=master)](https://travis-ci.org/vito16/shop) [![Coverage Status](https://coveralls.io/repos/github/vito16/shop/badge.svg?branch=master)](https://coveralls.io/github/vito16/shop?branch=master)

An online shopping project, continuously improving...

![Functional Map](img/module.png)

## Prerequisites
- Redis (On Windows, you can find a 3.0 installation package or use Docker; for Linux and Mac, the installation process is not elaborated here)
- Lombok plugin (For IntelliJ IDEA, install it yourself; I haven't tried it on Eclipse)
- MySQL database (>=5.7)

## Start the Service

    com.vito16.shop.Application.main()

Homepage: [http://localhost:8081/](http://localhost:8081/)  
Admin Panel: [http://localhost:8081/admin/login](http://localhost:8081/admin/login)  

## Configuration Modifications
You can modify relevant configurations in `application.properties` (HTTP server port, database configuration, etc.).

- Access port: server.port
- Database-related configurations: jdbc.***
- Initialization data script is located in `/src/main/resources/sql/`
- Admin credentials: admin/123456
- User credentials: vito16/123456
