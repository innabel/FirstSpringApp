First Spring Application

a simple application with use of Spring Core to see how Application Context works.
Main info:
- the project was created using Maven archetype - maven-archetype-webapp;
- structure of packages remains default (generated from the archetype structure) + README.md and a couple of .txt files were created;

Steps :
- pom.xml Maven configuration file edited  to add 3 main dependencies: Spring Core, Spring Beans, Spring Context;
- applicationContext.xml file added to resources folder to configure Spring Application Context;
- edited configuration file: Bean id and constructor-arg were added;
- in the main application class TestSpring the instance of our Bean was created;
- printed the field of our new instance using getter;