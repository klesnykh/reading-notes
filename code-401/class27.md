# Class 27 Reading Notes

**Thinking in React**  
1\. break down what you need the end result to look like into what components you will use, build out a version of the app with no usability, then make the MVP by using state, then make state better by dialing down which component state will live in, once that's done you're ready to implement code that alters the screen for the user when they actually want something updated  

**State: A Component's Memory**  
1\. Because you might need that data upon reload of the page or if you want to change the component based on user input  
2\. you need a way to retain data between renders and trigger react to render the component with new data. useState provides 1- a state variable to retain te data and 2- a state setter function to update the variable which triggers the render of the component  
3\. import useState from react, and then useState(whatever you want to use)  
