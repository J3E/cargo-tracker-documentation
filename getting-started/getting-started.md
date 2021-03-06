## Getting Started
Before exploring the code, it may be helpful to view a demo of the application functionality. You can do that through a [screen cast](http://git.delabassee.com/ct/demo.html) that covers most of the major functionality for Cargo Tracker.  

If you simply wish to explore the code, download it as a [Zip](https://cargotracker.java.net/#resources) or browse the [repository](https://github.com/J3E/cargo-tracker).  
The source is a Maven project, so you should be able to easily build it or set it up in your favorite IDE. We currently have instructions for [NetBeans](http://git.delabassee.com/ct/NetBeansHowTo.html) and we would welcome a contribution showing how to use the project with IntelliJ IDEA. Note that we currently do not recommend Eclipse due to it's poor support of Maven. For the detailed reasons, please look [here](https://java.net/jira/browse/CARGOTRACKER-76).  

You can also run the application directly from the Maven command line using Apache Cargo. All you need to is navigate to the project source root and type: ``mvn package cargo:run``  
Once the application starts up, just open up a browser and navigate to http://localhost:8080/cargo-tracker/.  

The project currently runs on Java EE 7/GlassFish 4 and Java SE 8 by default. You can also run the project using WebLogic 12.2.1 and Java SE 8 using [these instructions](http://git.delabassee.com/ct/WlsHowTo.html). We welcome contributions for running the application on other Java EE application servers (as you will see in the source code, there are few dependencies on GlassFish or WebLogic so this should be pretty easy to do).  

Our roadmap (see [these instructions](http://java.net/jira/browse/CARGOTRACKER)) includes plans to create a Java EE 6 version of the application.
