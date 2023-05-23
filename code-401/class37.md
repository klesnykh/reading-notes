# Class 37 Reading Notes

**Multiple Reducers Example**  
1\. Because it allows you to break up state into smaller chucks that are easier to test, read, etc  
2\. by using the combineReducers method  
3\. by dispatching actions, because state should only ever be changed by an action  

**Redux Docs: Using Combined Reducers**  
1\. redux reducers  
2\. it takes the different slices of your entire state and cobines their reducers into one  
3\. initial state would be the combined state of all of the separate reducers initial states you have  

**Redux Docs: Combined Reducer Syntax**  
1\. That is the basis of programming well. Any time a function starts having more than one thing it does you want to refactor it into two functions for ease of use and ease of testing. Same in reducers. The correct way is to have a reducer for each separate part of state  
2\. combineReducers, createStore  
3\. name what it changes in state  
