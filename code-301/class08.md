# Class 08 Reading Notes

**API Design Best Practices**  
1\. Representational State Transfer  
2\. resources, which are any kind of object, data, or service that can be accessed by the client  
3\. a URI that uniquely identifies that resource. Ex: https\://localhost:3001/weather?search=Seattle - I think this works as a URI however I'm not sure what makes a URL a URI  
4\. GET, POST, PUT, PATCH, DELETE  
5\. nouns  
6\. already gave the example in 3, a bad example would be instead of /weather it being /check-weather or something like a verb  
7\. It means an the API exposes a large nuber of small resources. Its good if there arent many resources lol, but bad if theres a ton  
8\. HTTP status code 200 (OK)  
9\. 404 not found  
10\. 201 (created) or 200 and include the result of the operation in the response body. If there is no result to return it would be a 204 (no content) with no response body  
11\. 204 (no content)  
