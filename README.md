# Simple LDAP simulating AD Integration test server.

This is a simple LDAP server that tries to simulate an AD using 
Apache Directory Server.

* Should work for activedirectory.js
* Is based on https://github.com/kwart/ldap-server/ and 
   http://stackoverflow.com/questions/11174835/add-memberof-attribute-to-apacheds 


## Docker

1. Build image `docker build -t dwimberger/ldap-ad-it .`
2. Run the image using  
   `docker run -it --rm -p 10389:10389 dwimberger/ldap-ad-it`


