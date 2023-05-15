# Class 31 Reading Notes

**Choosing the State Structure**  
1\. If 2 state variables always get updated at the same time, consider merging them, don't structure in a way that some pieces of state condradict other pieces, don't use it if it's not needed, don't use the same info in several state variables, don't nest  

**Passing State Deeply with Context**  
1\. Having to pass info through props down to several children  
2\. passing props, pass JSX as children  
3\. LevelContext?  
