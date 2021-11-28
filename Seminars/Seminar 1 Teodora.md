Teodora Postovan
https://cloud.google.com/architecture/microservices-architecture-introduction

•	What is the paper about? 
The paper describes monolithic and microservices-based application, studying some benefits and challenges of these microservices. In the last paragraph there is an explanation when and if there is a need to migrate from one microservice to another.

•	What is a monolithic application? 
As is stated in the paper, a monolithic application is a ‘’single-tiered software application”. If we explain to a person who is not in the field, then monolithic app – is a body where all the organs (in our case the modules), work as a whole. In fact monolithic would mean the classic application where all its components work hand in hand following the same paradigms and programming principles.

•	What is a microservices-based application? 
Microservices-based applications has the workflow splitted between a set of small and independent modules that perform and execute their own features. Moreover, each module can be written in a different programming language, has a database and communicate with the system through APIs.

•	In a paragraph, provide a comparative analysis between the 2 approaches. 
The difference between these microservices, is in the flexibility of building a whole system. If to refer to the monolithic app, then the developers are limited to use only one technology, with all restrictions and principles. But if the system is build using microservices-based application, then the developers have the flexibility to use different kind of technologies, programming languages, platforms etc. 
Another difference can be highlighted based on how the whole system is build, it's clear that if some errors occurs, in a monolithic app, the entire system can be affected and may fall, but for microservice-based app, since all services are isolated from each other, the errors that occur from one server doesn't affect the rest of the system.

•	Why would one want to migrate from one type of application to another?
To a monolithic app, we can migrate if the requirements are for the product to be tested and deployed, after each fix, as fast as possible. A single small unity (I think that most of all, small apps are built using monolithic approach) a fastest way to verify it's workflow. On the other hand we have the scalability that can be in a microservice based app, where the units(modules) are splitted between developers, and the whole complex system have now a good scalability, because each person know very well their own part of the system, and can easily delete, add, test new features.

•	When starting a new project, which approach is best? Why? 
I think it all depends on how complex the system needs to be developed. From the moment the requirements of the system are clear, we can understand which path to choose. For a simple application, which does not require large databases, a lot of logic, or various complex processes, can be chose the monolithic path of development. But once the system requires a multitude of processes and services to be implemented, each representing a big complexity, detailed testing, and continuous infiltration of new features, then the microservice approach will be the best.

•	How do these approaches compare in the context of maintainability?
Maintenance also depends on whether any changes need to be made during the entire vital process of the application. As I mentioned before, an application built according to the monolithic version can be difficult to maintain, once we have bugs that can affect the entire system, introduced with the development of a new feature, but if the system is well developed, and finished to be developed and works easily, maintenance is also easy. In a system based on microservices, maintaining the entire application can be easy, from the point of view that each team of developers knows quite well the part they worked on, and with the infiltration of new features, if an error occurs, we can easily target the service where it appeared. But maintenance in this large project, divided into multiple modules, can become more difficult, let's say, if a developer who does not know how the system works as a whole, and how the services relate to each other, will have full responsibility for maintaining all this huge project.

