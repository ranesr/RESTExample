RESTExample
===========

REST - Representational State Transfer

REST is an architectural style which is based on web-standards and the HTTP protocol.


HTTP Methods -

The PUT, GET, POST and DELETE methods are typical used in REST based architectures.


Softwares Used -

Eclipse Juno

Apache tomcat 7.0

Jersey 1.1


Prerequisites: Set up Tomcat run time environment in eclipse


Example -

1) Create a Dynamic web project in eclipse

2) Download these jar files -

   https://drive.google.com/folderview?id=0B77lFZEEiOpTUV84R2d6RC1yVlE&usp=sharing

   Save them to the folder WebContent/WEB-INF/lib

3) Import the files in this project to your project

4) Run the application on Tomcat server

5) Right click on the project and select Run on server and select Tomcat server. Once server is started hit the below url -

   http://localhost:8080/[Your-project-name]/services/convert/FeetToInch/2

   http://localhost:8080/[Your-project-name]/services/convert/InchToFeet/200
   
   You will see the output
