# JAVA EE
## Screenshot
![Project Screenshot](assets/java.png)
## Description
Project to learn how Java EE works. 

## Table of Contents
- [JAVA EE](#java-ee)
  - [Screenshot](#screenshot)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [JavaEE](#javaee)
  - [JSR](#jsr)
  - [Jakarta EE](#jakarta-ee)

## JavaEE
Is a set of abstruction which keeps you away from the actual implementation. i.e. If you want to persist some data into a database, you just 
need to use JAVAX bundle and call the respective package for the purpose. How the data is being processed and saved is all abstructed from the developer. 

## JSR
- Java Specification Request: Formal request to java community Process (JCP) for sugested changes into the APIs e.g. CDI 1 -> CDI 2
- It is used to group APIs into silos. 
- Here you can access all the JSRs (https://jcp.org/en/home/index)
  - For every JSR there is a Reference Implementation
- Reference Impmentation
  - Concrete realization of the abstract JSR
  - E.g. JAX-RS reference implementation - Jersey
  - JAVA EE itself is a JSR
  - An application server is a collection of various Reference implementations for JSRs in a bundle.
    - For instance: JAVA EE 8 is JSR 366 and Reference Implementation (RI) is Glassfish 5

## Jakarta EE
- Java EE going forward - there is a wider spectrum of people who going to develope which is hosted in Eclipse Foundation, and it is an addendum to Java EE. Basically has more features.  
- Hosted by Eclipse Foundation: Once every bit of change is sent to Eclipse foundation they deploy it. 
- https://jakarta.ee