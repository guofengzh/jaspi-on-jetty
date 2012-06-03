jaspi-on-jetty
==============

This is sample to demo how configure JASPI (JSR 196: JavaTM Authentication Service Provider Interface for Containers) for authentication on Jetty.

For detailed information, see https://bugs.eclipse.org/bugs/show_bug.cgi?id=359329

Usage: 
    1. launch Jetty: 
       mvn jetty:run -Dlogback.configurationFile=./conf/logback.xml
    2. acccess the protectd resource for authentication:
       http://localhost:8080/jaspi/protected/
