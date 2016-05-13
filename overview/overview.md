# Cargo Tracker

## Applied domain-driven design blueprints for Java EE

###Overview
This project demonstrates how you can develop applications with the Java EE platform using widely adopted architectural best practices like Domain-Driven Design (DDD). The code is intended to mirror a non-trivial application that developers in the real work would work on. It attempts to demonstrate first-hand how you can use Java EE to effectively meet practical enterprise concerns such as productivity, agility, testability, flexibility, maintainability, scalability and security.  

The project is directly based on the well known original [Java DDD sample](http://dddsample.sourceforge.net/) application developed by DDD pioneer Eric Evans' company [Domain Language](http://domainlanguage.com/) and the Swedish software consulting company [Citerus](http://www.citerus.se/). The cargo example actually comes from Eric Evans' [seminal book](http://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215). That project uses older versions of Spring, Hibernate and Jetty whereas we focus on vanilla Java EE.  

In the same vein as that project, we certainly are not in the business of prescribing how you should write Java EE applications. The code simply demonstrates ideas that you could adopt if you think they are right for you. We've also tried to show you just some of the many different approaches that you could take to interpret and implement DDD concepts. You are of course warmly welcomed to provide feedback and contribute to this Open Source project.  

As such, we will continue to rely heavily on the original DDD sample application as well as the existing knowledge base in the DDD community as invaluable resources on further details on DDD as it applies to this code base (please see the [Resources page](https://java.net/projects/cargotracker/pages/Resources) for vital details). We also highly recommend you read the[DDD and Java EE](https://java.net/projects/cargotracker/pages/Home#DDD_and_Java_EE) section. It is perhaps best to skim it, explore the application/code and revisit the section.  

This effort is very grateful for the kind blessings and guidance of the good folks behind the original DDD sample application.

###GOALS
* Demonstrate well established architectural patterns/blueprints for enterprise development with Java EE using pretty close to a real world application.
* Demonstre a concrete implementation of DDD concepts.
* Showcase some core Java EE technologies.

Contrary to beliefs long held by some folks, Java EE does not attempt to be a walled garden. Like all open standards, the goal of Java EE is to provide a reliable core standard foundation that a vibrant ecosystem of plug-ins and extensions can be built around. In that spirit, we will incorporate a select set of representative tools that complement Java EE well such as Maven, JUnit, Cargo, JMeter, soapUI, Arquillian, PrimeFaces and DeltaSpike.

###NON-GOALS
*   Comparison with other technologies such as Spring, .NET and Ruby on Rails. We suggest you do your own research using the plethora of good information already available. This project is squarely about showing you how you could write good Java EE applications and nothing else.
*   Attempting to demonstrate the very wide gamut of Java EE APIs and features. While we do incorporate a pretty representative set of Java EE APIs and features, it is not our goal to serve as a kitchen sink of comprehensive Java EE samples. The GlassFish samples project serves that purpose far better than us.
*   While it is certainly possible to learn certain aspects of Java EE (primarily how to architect good Java EE applications), this project is not intended to teach you the basics of Java EE. The official Java EE Tutorial and First Cup starter applications are intended as basic learning tools for Java EE.

