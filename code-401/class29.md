# Class 29 Reading Notes

**Extracting State Logic into a Reducer**  
1\. You get one fuunction that handles a bunch of different state changes, it's very scalable.  
2\. The actions are what kind of action you want to happen. They are not too much different than setting state directly, it seems like just another way to do it, but the reducer method becomes really helpful with larger builds, and naming your actions helps people understand why you want to change state  
3\. the .reduce method, because it...reduces the state and returns it to you in an array  
4\. You should switch from useState to useReduce when you start dealing with a lot of different state properties that do/trigger different things  
