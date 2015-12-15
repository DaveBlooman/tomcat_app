Example Cloudformation Tomcat App
==================


Cloudformation that creates an EC2 instance with an elastic load balancer, which uses Tomcat to serve a hello world app.

### App

Tomcat app.  Two routes, / and /sample/

### Cloudformation

Using user data, the docker package is installed, started and used to pull the packages needed.  Tomcat unpacks the sample apps to create the hello world app
