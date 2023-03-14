# Class 12 Reading Notes

**Status Codes Based On REST Methods**  
1\. -  

* 100's = the initial part of the request has been made
* 200's = success
* 300's = resource isn't available where it is expected
* 400's = client side input is wrong for the request
* 500's = server error, check server

2\. request valid, but processing will finish sometime in the future  
3\. tells client to use another URL to access the resource and not use the current one anymore  
4\. 204-no content  
5\. 410-Gone  
6\. "403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource."  

**Build A REST API With Node.....**  
1\. so we can use our db, the string is our database connection  
2\. code that runs when your server starts but before it gets to your routes  
3\. lets our server accept json  
4\. it means its a parameter  
5\. put updates all the info all at once, patch updates just the one thing  
6\. new mongoose.Schema plus keys  
7\. server encountered an unexpected condition that prevented it from fulfilling the request  
8\. 200 is just everything is ok vs 201 is a new resource has been created  
