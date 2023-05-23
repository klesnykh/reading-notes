# Class 36 Reading Notes

**Dan Abramov Redux Tutorials**  
1\. Represent the whole state of your entire JS App with a single JS object state  
2\. store holds the state and lets you dispatch actions through reducers  
3\. getState: gets the current state of the redux store, dispatch: lets you dispatch actions to change the state of your application, subscribe: allows you to register to the state that i guess listens to the state being updated and updates components based on that?  
4\. it's in the name, it allows you to combine reducers into one. The point of this is to make one store that uses one reducer, you don't want multiple stores  
