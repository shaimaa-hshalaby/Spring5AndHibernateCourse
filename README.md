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
   
   
