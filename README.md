# Spring-Framework Architecture
In this Document we are going to explain each and every spring framework part. 

![Spring Freamwork Architechar drawio (1)](https://user-images.githubusercontent.com/73180409/228052934-a14f49b2-deb2-451c-84a0-e97810325eb8.png)


## The Core Container is also known as the "Spring IoC Container" or the "Spring Application Context". It provides the infrastructure for managing and wiring together the components of a Spring-based application.

Within the Core Container, there are several important concepts, including the Core, beans, Context, and SpEL (Spring Expression Language).

1. Core: The Core refers to the foundational features of the Core Container, including its core interfaces, classes, and implementations.
2. Beans: In the context of the Spring Framework, a bean is an object that is managed by the Core Container. Beans are created, configured, and managed by the container, and can be defined in XML, Java, or through annotations. Each bean has a unique identifier, and can have dependencies on other beans.
