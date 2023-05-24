# Class 38 Reading Notes

**async actions**  
1\. to be able to write logic that has side effects  
2\. the middleware would pick up the dispatch first, can do anything it wants to it like fetching data from an API, and then passes it to the reducer  
3\. in our toDo app we'll need middleware to do anything that is API related  

**thunk middleware**  
1\. it allows us to write functions that can use our stores dispatch and getState functions  
2\. function  
3\. as the return value of dispatch itself  
