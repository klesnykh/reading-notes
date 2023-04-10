# Class 06 Reading Notes

**Securing Passwords**  
1\. basically take a users password and transform it into data that can't be converted back to the original passoword, and then pass that into some sort of database  
2\. its a slow password hashing function  
3\. because its more secure  

**Basic Auth**  
1\. its a method for an http user agent to provide a username and password when making a request  
2\. the Base64 encoding of an ID and password joined by a single colon  
3\. Base64  

**OWASP auth cheatsheet**  
1\. It basically just checks if a user is who they claim to be  
2\. In a generic manner, because otherwise a user who is trying to gain access would know what part they got wrong and what they need to alter (userID/password enumeration)  
