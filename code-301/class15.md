# Class 15 Reading Notes

**What is OAuth?**  
1\. An internet framework we can incorporate into our code that grants user access to websites we write  
2\. Using google to sign into a website not google related  
3\. first and second website connect using 0Auth, second website creates a one time token and secret, and then the client checks if thats them and allows connection  
4\. "OpenId is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans"  

**Authorization and Authentication flows**  
1\. Authorization is "ask:allow" vs Authentication is "is this you?true:false"  
2\. exchanges an Athorization Code Flow for a token  
3\. Its auth code flow plus additional security: makes use of a proof key for code exchange (PKCE)  
4\. An alternative for Auth Code Flow that only needs an ID token to perform user authentication  
5\. A way to authorize the app rather than the user  
6\. A method of authentication that requires the user to go to another device to authorize the new device  
7\. Typical username and password authentication  
