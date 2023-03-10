# Spring 5 And Hibernate Course
My Spring 5 and Hibernate Course layout and details 

I believe that we should start from the beginning to deeply understand the magic of the spring boot. So in my courses, I start from the XML configuration step by step untill we reach to the latest code snippets of spring boot and microservices.



## Spring Core Module

  ### Spring core Lab Exercises
  
  

  **1- Spring Core with XML Configuration**
  
  
   - How to download/add Spring 5 jar to the classpath
   - Create a Maven project and add Spring core and spring context dependency
   - Using XML to define the beans
   - proof the concept of Inversion of control(create the spring context, get the beans from the context and invoke the bean logic)
   - Configure costructor/setter injection in XML
   - Configure reading literal values from the context XML file
   - Configure reading literal values from the properties file
   - Test memory Addresses of 2 objects of a Singleton bean
   - define Bean with a prototype Scope 
   - Test memory Addresses of 2 objects of a prototype bean
   - Define Bean Life Cycle and add them to the XML configuration


**2- Spring Core with Annotation and XML Configuration**
  
   - Use @Component annotation to define the beans
   - Use @Autowired annotation for the dependency injection 
      - Constructor injection
      - Setter injection
      - Field injection
   - Use @Value annotation and expression language to read literal values from the properties file
   - Define Bean Life Cycle methods by using @PostConstruct and @PreDestroy
   
 
 **3- Spring Core with Annotation and Java Configuration - No XML**
 
 - Use @Configuration annotation to define Configuration class 
 - Use @ComponentScan annotation to define the base package to scan for the components
 - use @PropertySource annotations to define the properties file and read the properties by @Value annotation
 - define a bean inside the configuration file using @Bean annotation
 - dependency injection by code and @Bean annotation in the Configuration file
   
---------
 
## Spring MVC Module

### Spring MVC Lab Exercises


---------
 
## Spring AOP Module

### Spring AOP Lab Exercises

  - Create Maven Project and add the needed dependency for the Spring core &  Aspectj
  - Enable the aspect feature by using @EnableAspectJAutoProxy in the Configuration class
  - Create Aspect Advice Class
  - Use @Before() annotation and test execution
    - Test pointcut expression for specific method name
    - Test pointcut expression for specific method & specific class
    - Test pointcut expression for wild card method name
    - Test pointcut expression for wild card return type
    - Test pointcut expression for a method with a specific param type (Complex type)
    - Test pointcut expression for a method with wild card parameters
    - Test pointcut expression for any method in a specific package

  - Use @Pointcut annotation to declare a pointcut expression and use it for multiple advices
  - Create Pointcut expression to be executed before any method in the package and exclude setters and getters method
  - Create Class to save the pointcut expressions and reuse them
  - Use @Order annotation to order the aspects
