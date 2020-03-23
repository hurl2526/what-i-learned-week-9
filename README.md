# **What I Learned Week 9**
## **Day 32**   

Went over hw

Started Grid

Display: grid instead of flex  

example:

Grid-template-rows:

.square {
  width: 100px;
  height: 100px;
  background-color: blue;
  border: 2px solid red;
  font-size: 5em;
  color: green;
}

.container {
  display: grid;
  height: 300px;
  width: 300px;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
}

#item-3 {
  background-color: orange;
  grid-row: 1 / span 1;
  grid-column: 2 / span 1;
}  
## **Day 32**

Went over grid hw and code wars

Started new project


Docqueryselect an element    

learned how to add class using classlist..  

Thatelement .classlist.add('add some class you create')

Also .remove or .toggle  

learned shortcuts like:  
repeat(10, 1fr)
repeat(5, 20%)

## **Day 33**

More indepth on .classList and working on project

replace is short hand for remove and add but is better because if the thing being removed isn't there it wont add

also shows how to use with index

Example: this will remove the second class and add a new class called color-2

currentSelection.classList.remove(currentSelection.classList[1]);
currentSelection.classList.add('color-2’);

console.log('Welcome to classList!');

const item1 = document.querySelector('#item-1');
const item3 = document.querySelector('#item-3');

console.log(item1.classList);
console.log(item3.classList);

const firstClass = item3.classList[0];
const secondClass = item3.classList[1];
console.log('firstClass is: ', firstClass);
console.log('secondClass is: ', secondClass);

// item3.classList.toggle(firstClass);
// item3.classList.toggle(firstClass);
// item3.classList.toggle(firstClass);
// item3.classList.toggle(firstClass);

}
item3.classList.replace('big', 'black-border-centered');
item3.classList.replace('black-border-centered', 'big');


item3.classList.replace(item3.classList[1], 'black-border-centered');

item3.classList.replace('small', 'big');

if (item3.classList.contains('small')) {
  item3.classList.remove('small');
  item3.classList.add('big');






**keyboard shortcuts to remember**  
* multiplt cusors: click at end of one word 
* option click at end of another word.
* Also, highlight a word and then click command D to grab the next of same word  
* select word, command shift L selects them all