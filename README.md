spring-ex13-auth
======================

This example builds on spring-ex12-auth, where we customized the access denied (403) page.  In this example, we add method level role based security to our strategy controller.  We only add one line to our security config and one line to our controller in order to enable this security.  This example uses Spring 4.0.2 and Spring Security 3.2.3, and uses java configuration files rather than XML.

This example has been validated with the following environment on MS Windows 7:

1. Eclipse Kepler
   1.1 Spring Tool Suite (STS) 3.4.0.RELEASE - for Kepler
2. Java SDK 1.7.0_51 (separate install)
3. Tomcat 7.0.50 (separate install)
4. Maven 3.0.5 (separate install)
5. MySQL 5.5.29
