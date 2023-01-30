# Class 06 Reading Notes

*JavaScript Objest Basics*  
1\. An object is basically something that has different attributes inside with values to those attributes. Like for roman numerals you can have an object that has basically a list of key:value pairs like I: 1, V: 5, X: 10, but you can have different objects with different lists of keys, attributes, whatever with a value assigned to them like age, hair color, whatever. The value to an object can be anything  
2\. Advantages of object literal are that they hold multiple values, so if you need to call out those values one by one it can be more efficient to just call out the object, and you can even store objects as object properties kind of like you can store arrays inside arrays, but using an object might be simpler depending on the task  
3\. Objects and arrays are actually almost the same, one difference is just how they're made up and how you can access stuff inside them  
4\. If an objects property name is held in a variable  
5\. "this" refers to the current object the code is being written inside (in this (lol i just used this) case its dog). The benefit is that if you're creating a lot ob object literals it will give you better efficiency. It's quicker and easier  

*DOM*  
1\. The Document Object Model is the data representation of the objects that comprise the structure and content of a ducument on the web.  
2\. The DOM allows programming languages to interact with the page, so it allows us to write code and make the page do what we want it to do.  

<!-- /*
3 steps to render to the DOM
- 1. create an element
declare a variable and then call createElement() and pass the html tag name as a string to createElement */
let kittenArticle = document.createElement('article');

/*
- 2. give it content
- 3. append it to the DOM, use appendChild() */
profileContainer.appendChild(kittenArticle);

// follow steps to create an h3 heading for a new element
// h3
let kittenH3 = document.createElement('h3');
kittenH3.textContent = 'Jumper'; //gives content (step 2) to the h3 element
kittenArticle.appendChild(kittenH3);

// p
let p = document.createElement('p');
p.textContent = 'Jumper the cat is wonderful';
kittenArticle.appendChild(p);

// img
let img = document.createElement('img');
img.src = 'images/jumper.jpg';
img.alt = 'Jumper is very cute';
kittenArticle.appendChild(img);

document.querySelector('article:nth-child(2) h3'); //this show <h3>Jumper</h3>

let li = document.createElement('li');
li.textContent = `6am: ${seattle.someValueInArray}`;

let jumper = {
    name: 'Jumper',
    likes: ['catnip', 'food', 'string'],
    renderList = function(){
        let ul = document.createElement('ul');
        
        for (let i=0; i<this.likes.length; i++){
            let li = document.createElement('li');
            li.textContent = this.likes[0];
            ul.appendChild(li);
        }
        
    }
} -->