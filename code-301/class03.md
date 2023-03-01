# Class 03 Reading Notes

**React Docs - lists and keys**  
1\. returns a new array  
2\. .map(value => {console.log(value)});  
3\. key  
4\. to keep track of what's been changed  

**The Spread Operator**  
1\. "The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments"  
2\. copying an array, using math functions, combining objects, adding an item to a list  
3\. let newArr = [...arrOne, ...arrTwo]  
4\. let newArr = [-1, 0, ...arrOne]  
5\. objOne={adjective: "beast"}, objTwo={isHe: true}  
let beast = {...objOne, ...objTwo}  

**How to Pass Functions Between Components**  
1\. he adds it into the render as a function by using this.function  
2\. in the example it just changed the state counter  
3\. this.function
4\. this.props.function()  
