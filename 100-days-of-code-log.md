# 100 Days Of Code - Log - Lahiru Liyanapathirana 
#### Start Date : July 04, 2018 | Status : In Progress

---

### Day 1: July 04, 2018

#### Task : Creating a REST API with Vert.x
#### Progress: 

I started learning Vert.x framework by Eclipse recent. And I had already created a project with Vert.x to create REST API. Basic skeleton of the project is already done. I have yet to do the improvements, such as backing the API with a MySql db, improve the REST endpoints of the API. As the first day of the challenge I plan to add MySQL support to the API. Created a test implementation for MySql, also improved the REST endpoints by allowing headers and HTTP methods.

#### Link to work : [https://github.com/LahiruTjay/vertx-rest-api]

---

### Day 2: July 05, 2018

#### Task : Creating a REST API with Vert.x
#### Progress: 

Off to a bad start today. Not much was implemented. Just added some changes to the User Router and added initial JDBC configuration.

#### Link to work : [https://github.com/LahiruTjay/vertx-rest-api]

---

### Day 3: July 06, 2018

#### Task : Creating a REST API with Vert.x
#### Progress: 

JDBC configuration updated and managed to retrive data from the DB with async JDBC client. Still some parts are confusing, specially with the callbacks. Need to look futher into Java's "Future" and Vert.x "Future".

#### Link to work : [https://github.com/LahiruTjay/vertx-rest-api]

---

### Day 4: July 07, 2018

#### Task : Creating a REST API with Vert.x
#### Progress: 

Managed to generalize the DB methods to support generic queries upto an extent. Needs further improvements. Refactored the architechture of the project. But not satisfied with it. Need to look into it more. Or possibly get expert advice on the matter.

#### Link to work : [https://github.com/LahiruTjay/vertx-rest-api]

---

### Day 5: July 08, 2018

#### Task : Creating a REST API with Vert.x
#### Progress: 

All REST end points for one service are completed. API seems to be working ok. Need to add a proper error handling mechanism. Also architecture needs to be changed. 

#### Link to work : [https://github.com/LahiruTjay/vertx-rest-api]

---

### Day 6: July 09, 2018

#### Task : Creating a REST API with Vert.x
#### Progress: 

Added common HTTP error handlers, and also added default 404 handler for the REST API. Need to look into Java generics to handle generic object return for the database queries.

#### Link to work : [https://github.com/LahiruTjay/vertx-rest-api]

---

### Day 7: July 10, 2018

#### Task : Micro-services with Spring boot
#### Progress: 

The Vert.x REST API is kept on hold for sometime. Started working on microservices architecture using Spring boot. As the inital step created a maven multi module project skeleton, which i haven't done earlier. Have to look into microservices with Spring boot and thoroughly understand the core concepts. 

#### Link to work : [https://github.com/LahiruTjay/spring-boot-microservices]

---

### Day 8: July 11, 2018

#### Task : Micro-services with Spring boot
#### Progress: 

Not much of coding today. Just looked at a few videos on microservices with spring to get an idea about the core concepts.

#### Link to work : [https://github.com/LahiruTjay/spring-boot-microservices]

---

### Day 9: July 13, 2018

#### Task : Micro-services with Spring boot
#### Progress: 

July 12 : Had to skip because of some urgent work. Double time today. 

July 13 : Created the eureka discovery service and a eureka client. Had a tough time with multi module pom.xml dependencies. Have to look into pom.xml dependency management

#### Link to work : [https://github.com/LahiruTjay/spring-boot-microservices]

---

### Day 10: July 14, 2018

#### Task : Micro-services with Spring boot
#### Progress: 

Configured a rest client to call a rest endpoint through the eureka discovery server. Came across a few bumps in the road, but managed to fix them. Need to understand the concepts of discoery services and look into eureka. Also need to look into circuit breaker pattern with Hystrix.

#### Link to work : [https://github.com/LahiruTjay/spring-boot-microservices]

---

### Day 11: July 15, 2018

#### Task : Micro-services with Spring boot
#### Progress: 

Added hystrix circuit breaker to the api gateway. Added the fallback methods as well. Also managed to configure zuul proxy. Need more time to properly understand both hystrix and zuul.

#### Link to work : [https://github.com/LahiruTjay/spring-boot-microservices]

---

### Day 12: July 16 & 17, 2018

#### Task : Real-time Event Processing with Spring Webflux
#### Progress: 

Yesterday and today was working on an article about Webflux framework of Spring ecosystem. Worked with event streaming with Webflux. Created a simple web server which produced an event stream, and a web client which consumes and logs the stream. 

#### Link to work : []

---

### Day 13: July 18, 2018

#### Task : Real-time Event Processing with Spring Webflux
#### Progress: 

Managed to finish the article and submit. Not much coding today. But looked into Hystrix circuit breaker and the fallback methods of it.

#### Link to work : []

---