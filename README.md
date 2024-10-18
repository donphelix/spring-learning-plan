# spring-learning-plan
# Spring Topics Learning Plan

## 1. Spring Security
Spring Security is a powerful and customizable authentication and access-control framework for securing Spring-based applications.

- **Authentication**: Process of verifying who the user is.
- **Authorization**: Process of verifying what the user is allowed to access.
- **JWT (JSON Web Token)**: A compact, URL-safe means of representing claims to be transferred between two parties.
- **Spring Security OAuth2**: Integrates Spring applications with third-party authentication providers like Google or Facebook.
- **Spring Security Test**: Tools to help test the security of your application.
- **Spring Security ACL**: Access Control List implementation to define fine-grained permissions for users.
- **Spring Security LDAP**: Integration with LDAP servers for authentication.
- **Spring Security JAAS**: Java Authentication and Authorization Service support.
- **Spring Security SAML**: Integration with SAML 2.0 identity providers.
- **Spring Security OpenID**: Integration with OpenID identity providers.
- **Spring Security CAS**: Central Authentication Service integration.
- **Spring Security Kerberos**: Authentication based on the Kerberos protocol.
- **Spring Security Remember Me**: Persistence of user login sessions.
- **Spring Security CSRF**: Cross-Site Request Forgery protection.
- **Okta**: A cloud-based platform to manage authentication and authorization.
- **Keycloak**: Open-source identity and access management.

## 2. Spring Boot Scheduler
Spring Boot provides support for scheduled tasks with a variety of scheduling options.

- **@Scheduled(cron = "...")**: Cron expression to define precise scheduling, e.g., daily at midnight.
- **@Scheduled(fixedDelay = ...)**: Executes after a fixed delay between task completions.
- **@Scheduled(fixedRate = ...)**: Executes at a fixed rate regardless of task completion.
- **@Scheduled(initialDelay = ..., fixedDelay = ...)**: Executes after an initial delay and continues with a fixed delay.
- **Shedlock**: Prevents multiple instances of the same job from running simultaneously.
- **Quartz**: A job scheduling library that can be integrated with Spring.

## 3. Spring Boot Actuator
Actuator provides production-ready features to help monitor and manage your Spring Boot application.

- **/health**: Endpoint to check the health status of the application.
- **/info**: Displays information about the application.
- **/metrics**: Provides various metrics, like memory usage.
- **/loggers**: Enables dynamic configuration of logging levels.
- **/heapdump**: Dumps the heap for troubleshooting.
- **/threaddump**: Dumps thread information for analysis.
- **/beans**: Displays all Spring beans in the application.
- **/env**: Shows environment properties.
- **/mappings**: Displays request mappings of the application.
- **/scheduledtasks**: Lists scheduled tasks.
- **/httptrace**: Displays HTTP requests and responses.
- **/auditevents**: Displays security-related events.
- **/shutdown**: Shuts down the application.
- **/refresh**: Refreshes the application configuration.
- **/pause**: Pauses the scheduled tasks.
- **/resume**: Resumes paused tasks.

## 4. JPA Caching
Caching improves performance by minimizing database access.

- **First-level Cache**: Cache maintained by the EntityManager for the lifecycle of a session.
- **Second-level Cache**: Cache maintained at the provider level (e.g., Hibernate).
- **Query Caching**: Stores the results of queries for reuse.
- **Collection Caching**: Caches results of collections to reduce database calls.
- **Cache Regions**: Logical grouping of cacheable entities.
- **EhCache**: Default cache provider for Hibernate.
- **Infinispan, Hazelcast, Coherence**: Other cache providers supported by Hibernate.

## 5. Hibernate Caching
Hibernate provides first and second-level caching mechanisms.

- **First-level Cache**: Maintained by the session, a short-lived cache.
- **Second-level Cache**: Maintained by the SessionFactory, shared among all sessions.
- **Query Cache**: Caches query results for reuse across multiple sessions.

## 6. Distributed Transactions in Microservices
Managing transactions across microservices can be challenging, and different strategies are used to ensure consistency.

- **Saga Pattern**: Breaks down transactions into a series of local transactions.
- **Two-phase Commit (2PC)**: Ensures all participants agree to commit a transaction.
- **XA Protocol**: A standard for distributed transaction processing.
- **1PC, 2PC, 3PC, 4PC, 5PC**: Varying protocols for coordinating distributed transactions.
- **TCC (Try-Confirm-Cancel)**: Ensures distributed consistency by trying an operation, confirming, or canceling it.
- **BASE vs. ACID**: Different approaches to handling consistency in distributed systems.
- **CAP Theorem**: Defines trade-offs between Consistency, Availability, and Partition Tolerance.

## 7. Microservices Communication
Microservices must communicate reliably, and several methods are used to ensure communication.

- **REST**: HTTP-based communication between services.
- **SOAP**: XML-based protocol for service communication.
- **RPC**: Remote Procedure Call for invoking methods in distributed systems.
- **Message Broker**: Asynchronous communication via brokers like RabbitMQ and Kafka.
- **RabbitMQ**: A messaging broker for microservices communication.
- **Apache Kafka**: Distributed event-streaming platform.

## 8. Microservices Security
Security for microservices requires specialized strategies.

- **OAuth2**: Token-based authentication and authorization.
- **JWT**: Commonly used with OAuth2 to pass user information securely.
- **Spring Security**: Framework for securing Spring-based microservices.

## 9. Microservices Deployment
Deployment of microservices involves specialized tools and practices.

- **12-factor app**: A methodology for building modern, scalable applications.
- **Docker**: Containerization platform to deploy applications in isolated environments.
- **Kubernetes**: Orchestration system for automating deployment, scaling, and management of containerized applications.

## 10. Microservices Monitoring
Monitoring is essential to maintain the health and performance of microservices.

- **Prometheus**: Monitoring and alerting toolkit.
- **Grafana**: Analytics and monitoring platform.

## 11. Microservices Logging
Logging is critical for debugging and maintaining microservices.

- **ELK Stack**: Elasticsearch, Logstash, and Kibana for logging and analyzing logs.
- **12-factor app**: Logging practices for modern applications.

## 12. Microservices Testing
Testing is crucial to ensure the reliability of microservices.

- **Unit Testing**: Testing individual components in isolation.
- **Integration Testing**: Testing how components interact with each other.

## 13. Microservices CI/CD
Continuous Integration and Continuous Deployment (CI/CD) streamline microservices delivery.

- **Jenkins**: Automation server for building, testing, and deploying code.
- **12-factor app**: Guidelines for CI/CD.

## 14. Microservices Versioning
Versioning is essential to manage changes in microservices APIs.

- **Semantic Versioning**: A versioning scheme that uses major, minor, and patch numbers.

## 15. Microservices Documentation
Good documentation ensures that microservices are easy to understand and use.

- **Swagger**: API documentation and interaction tool.

## 16. Microservices Best Practices
Adopting best practices ensures efficient and maintainable microservices.

- **12-factor app**: Best practices for microservices.
- **Microservices Patterns**: Common architectural patterns used in microservices.

## 17. Microservices Architecture
Understanding different architectures can guide decisions on whether microservices or monolithic approaches are suitable.

- **Monolithic Architecture**: All components reside within a single system.
- **Microservices Patterns**: Patterns like Service Mesh, Circuit Breaker for designing microservices.

## 18. NoSQL Databases
NoSQL databases provide flexible schemas for storing data.

- **MongoDB**: Document-based NoSQL database.
- **Cassandra**: Distributed NoSQL database.
- **Redis**: In-memory key-value store.
- **CouchDB**: Document-oriented NoSQL database.
- **Riak**: Key-value NoSQL database.

