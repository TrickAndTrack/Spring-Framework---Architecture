# Spring-Framework Architecture
In this Document we are going to explain each and every spring framework part. 

![Spring Freamwork Architechar drawio (1)](https://user-images.githubusercontent.com/73180409/228052934-a14f49b2-deb2-451c-84a0-e97810325eb8.png)


### The Core Container is also known as the "Spring IoC Container" or the "Spring Application Context". It provides the infrastructure for managing and wiring together the components of a Spring-based application.

Within the Core Container, there are several important concepts, including the Core, beans, Context, and SpEL (Spring Expression Language).

1. Core: The Core refers to the foundational features of the Core Container, including its core interfaces, classes, and implementations.
          The Core module provides the fundamental parts of the framework, including the IoC and Dependency Injection features.

2. Beans: In the context of the Spring Framework, a bean is an object that is managed by the Core Container. Beans are created, configured, and managed by the container, and can be defined in XML, Java, or through annotations. Each bean has a unique identifier, and can have dependencies on other beans.
The Core module provides the fundamental parts of the framework, including the IoC and Dependency Injection features.

3. Context: The Context module builds on the solid base provided by the Core and Beans modules.The Application Context interface is the focal point of the.

4. SPEL: The Spring Expression Language (SpEL) is a powerful expression language that allows you to dynamically evaluate expressions at runtime.

### Data Access/Integration: are supported through various modules and APIs, including JDBC, ORM, OXM, JMS, and Transactions. Here's a brief overview of each of these modules:


1. JDBC: The Spring JDBC module provides a JDBC-abstraction layer that simplifies the use of JDBC and makes it easier to work with relational databases. It provides features such as exception translation, automatic transaction management, and SQL error handling.

2. ORM: The Spring ORM module provides integration with different Object-Relational Mapping (ORM) frameworks, such as Hibernate, JPA, and MyBatis. It provides a consistent and easy-to-use API for working with database entities and supports features such as transaction management and caching.

3. OXM: The Spring OXM module provides integration with different Object-XML Mapping (OXM) frameworks, such as JAXB, Castor, and JiBX. It allows you to marshal and unmarshal objects to and from XML.

4. JMS: The Spring JMS module provides support for working with Java Message Service (JMS) providers, such as Apache ActiveMQ, IBM MQ, and RabbitMQ. It provides features such as message sending, receiving, and transaction management.

5. Transactions: The Spring Transactions module provides a consistent programming model for managing transactions across different transaction APIs, such as JDBC, JPA, and JMS. It provides declarative transaction management, which allows you to define transactions using annotations or XML configuration.

6. Overall, these modules provide a comprehensive set of tools for accessing and integrating with different data sources and technologies. They simplify and streamline data access and integration tasks, reducing the amount of boilerplate code required for common operations and providing a consistent programming model for managing transactions.

### Web module provides basic web-oriented integration features such as multipart file-upload functionality and the initialization of the IoC container using servlet listeners and a web-oriented application context.

1. Web-MVC- he Spring Web-MVC module provides a Model-View-Controller (MVC) framework for building web applications. It includes features such as handler mapping, view resolution, and data binding. It also supports RESTful web services through the use.

2. Web-Socket- module provides support for WebSocket-based, two-way communication between the client and the server in web applications.

3. Web-Portlet- module provides the MVC implementation to be used in a portlet environment and mirrors the functionality of Web-Servlet module.

### Miscellaneous

AOP: The Spring AOP (Aspect-Oriented Programming) module provides support for implementing cross-cutting concerns, such as logging, transaction management, and security, in a modular and reusable way. It allows you to separate the implementation of these concerns from the main business logic of your application, improving modularity and maintainability.

Aspect: The Spring Aspect module provides support for defining and using aspects, which are reusable modules that encapsulate cross-cutting concerns. It includes features such as pointcuts, advice, and join points, which allow you to define where and how aspects should be applied.

Messaging: module provides support for STOMP as the WebSocket sub-protocol to use in applications. It also supports an annotation programming model for routing and processing STOMP messages from WebSocket clients

Text: module supports the testing of Spring components with JUnit

Instrumentation: module provides class instrumentation support and classloader implementations to be used in certain application servers.
