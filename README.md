# Web services project with Spring Boot and JPA/Hibernate

This is a small project made with the intention of learning and practicing Spring framework while using JPA/Hibernate tools. It's the back-end application of a simulated online store, with products from different categories that can be ordered by multiple users. This study project is an exercise from [DevSuperior's](https://github.com/devsuperior) Java course.

## Technologies used
- Java
- Spring Boot
- Apache Tomcat
- JPA/Hibernate
- Maven
- H2 Database

## Domain model
![Domain](https://github.com/pedrosrfm/workshop-springboot3-jpa/blob/main/assets/domain_model.png)

## Layers
![Layers](https://github.com/pedrosrfm/workshop-springboot3-jpa/blob/main/assets/layers.png)

## Code snippets
### Object requests
#### Product

```json
  {
        "id": 1,
        "name": "The Lord of the Rings",
        "description": "Lorem ipsum dolor sit amet, consectetur.",
        "price": 90.5,
        "imgUrl": "",
        "categories": [
            {
                "id": 2,
                "name": "Books"
            }
        ]
  }
```
#### Users
```json
[
    {
        "id": 1,
        "name": "Maria Brown",
        "email": "maria@gmail.com",
        "phone": "988888888",
        "password": "123456"
    },
    {
        "id": 2,
        "name": "Alex Green",
        "email": "alex@gmail.com",
        "phone": "977777777",
        "password": "123456"
    }
]
```


## My LinkedIn
https://www.linkedin.com/in/pedro-serafim-444157203/
