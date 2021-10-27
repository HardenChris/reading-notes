# Passing Functions as Props

## List and Keys

**What does .map() return?**

- A new array with the results of calling a function on every element in an array. And will have the same length as the original array,

**If I want to loop through an array and display each value in JSX, how do I do that in React?**

```const numbers = [1, 2, 3, 4, 5];```<br>
```const listItems = numbers.map((numbers) =>```<br>
```  <li>{numbers}</li>```<br>
```);```<br>
```ReactDOM.render(```<br>
```  <ul>{listItems}</ul>,```<br>
```  document.getElementById('root')```<br>
```);```<br>

**Each list item needs a unique ____.**

- key 

**What is the purpose of a key?**```

- keys help react id whe=at has been modified in some way be it added or removed.

## How to Use the Spread Operator (…) in JavaScript

**What is the spread operator?**

- allows for an arrays and other iterables to be to expands it to see/access individual elements.

**List 4 things that the spread operator can do.**

- use "Math." functions
- copy arrays
- combine various objects

**Give an example of using the spread operator to combine two arrays.**

```const listOne = [1,2,3]```<br>
```const listTwo = [4,5,6]```<br>
```const listMesh = [...listOne,...listTwo]```
```console.log(listMesh) // Array(6) [1,2,3,4.5,6]```<br>

**Give an example of using the spread operator to add a new item to an array.**

```const listOne = [1,2,3]```<br>
```const listTwo = [4,5, ...listOne]```<br>
```console.log(listTwo) // Array(5) [4,5,1,2,3]```<br>

**Give an example of using the spread operator to combine two objects into one.**

```const objectOne = {hello: dork}```<br>
```const objectTwo = {world: dorkette}```<br>
```const objectThree = {...objectOne, ...objectTwo}```<br>
```console.log(objectThree) // Object {hello: dork, world: dorkette}```

## React - How to Pass Functions between Components - Episode 22

**In the video, what is the first step that the developer does to pass functions between components?**

- first he creates a function where he wants the state to change.

**In your own words, what does the increment function do?**

- increment is a function that looks at the people state array and looks for the corresponding person to increase the count on that persons name. Every time the persons name is selected their 'count' counter will increase by one. 

**How can you pass a method from a parent component into a child component?**

- by using props. in the video he passes increment as a function with ```this.props.increment(this.props.name)```

**How does the child component invoke a method that was passed to it from a parent component?**

- the function listed above causes a state change and that state change will cause a rerender and then pass down the new value in props.

## Things I want to know more about


"Lists and Keys" reactjs, <https://reactjs.org/docs/lists-and-keys.html>

Dr. Austin, Derek. "How to Use the Spread Operator (…) in JavaScript" medium, 4 Oct 2019, <https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab>

"React - How to Pass Functions between Components - Episode 22" YouTube, uploaded by 
Steve Griffith - Prof3ssorSt3v3, 22 Oct 2018, https://www.youtube.com/watch?v=c05OL7XbwXU.

All definitions and information came from above listed publication(s).

[<===Back>](README.md)
