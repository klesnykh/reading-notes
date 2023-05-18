# Class 34 Reading Notes

**Review API Server Build**  
1\. query is what's after the ? mark, path is what's right after the main url, like /cookies or /books  
2\. http://our-site.com/v3/stuff/things  
3\. The interface just has a bucnh of routes you can go to, and you need to hook up a front end to that interface that sends those route requests in order to get data back and show the user  

**Review Auth Server Build**  
1\. middleware means that it would happen in between the request and response. What you would do is check if this user has the permissions/access for this request and let them through if they do  
2\. not sure if I remember it being a handshake, but you would send in the username and password and you would get a token back. Now you can use that token when making a request instead of passing in the username and password every time. It's definitely not like a socket connection handshake from what I remember.  
3\. I believe this was part of yesterday's reading as well. It basically just means that your app is checking if your user has the permissions/roles associated with the request the user makes, and if they do you allow it, if not...no  
