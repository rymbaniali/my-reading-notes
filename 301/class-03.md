
1.What does .map() return?
	new array of same length. in the ex. : return a <li> element for each item
2.If I want to loop through an array and display each value in JSX, how do I do that in React?
	WE can build collections of elements and include them in JSX using curly braces {}.
3.Each list item needs a unique ____.
	key.
4.What is the purpose of a key?
	Help React identify which items have changed, are added, or are removed.




5.What is the spread operator?
	The spread operator is a useful and quick syntax for adding items to arrays.
6.List 4 things that the spread operator can do.
	Copying an array,Adding an item to a list,Adding to state in React,and Combining objects.


7.Give an example of using the spread operator to combine two arrays?
	
const name = {name: "Ahmad"}
const age = {age: "25"}

const nameAge = {...Ahmad,...25}
	

8.Give an example of using the spread operator to add a new item to an array?
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]

9.Give an example of using the spread operator to combine two objects into one?

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂


10.In the video, what is the first step that the developer does to pass functions between components?
	use props
11.In your own words, what does the increment function do?
	change the state.
12.How can you pass a method from a parent component into a child component?
	by using props.the name of the method 
13.How does the child component invoke a method that was passed to it from a parent component?
	by state .