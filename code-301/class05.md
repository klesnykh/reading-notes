# Class 05 Reading Notes

**React Docs - Thinking in React**  
1\. It means one thing should only have one resposibility, one thing it does, or one thing that it is. For components that means they should only do one thing  
2\. It means to just build a site with no user intaraction, just a render  
3\. The minimum amount of state required for user interaction  
4\. Is it passed in via props, does it remain unchanged, and can you compute it with any state or props in your component?  
5\. Identify every component that renders something based on state, find a common owner component and that will own state, if it doesn't make sense to own it anywhere make another component somewhere higher in the hierarchy  

**Higher-Order Functions**  
1\. Functions that operate on other functions, either by taking them as arguments or by returning them  
2\. returns a true or false depending on if the number passed in is greater than 10 or not  
3\. map returns a function which returns something, and reduce does the same making them higher order functions  
