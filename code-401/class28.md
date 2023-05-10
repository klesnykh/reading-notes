# Class 28 Reading Notes

**useEffect Hook**  
1\. When you use useEffect, you pass it a function that will be executed after the component has rendered. React will remember this function and call it after every render. If you need to perform some cleanup when the component unmounts, you can return a function from the effect.  
2\. the effect starts when the page renders  
3\. it returns undefined, so not sure the importance of it, chatGPT says that you can also pass in a function into useEffect that does have a return value and that return value is used to perform cleanup tasks when the component unmounts or before the effect runs again due to state or props change
