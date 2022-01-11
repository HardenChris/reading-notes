# INode Ecosystem, TDD, CI/CD

## Component-Based Architecture

1. Describe (in plain English) what Array.map() does]

    - map function does a loop over an array and runs a function on each element.

    - > map calls a provided callbackFn function once for each element in an array, in order, and constructs a new array from the results. callbackFn is invoked only for indexes of the array which have assigned values (including undefined). -from site


2. Describe (in plain English) what Array.reduce() does

    - simple english..... reduce takes an array, and loops through it adding each element together until there is only one element left in the end. 

    - > The reduce() method executes a user-supplied “reducer” callback function on each element of the array, in order, passing in the return value from the calculation on the preceding element. The final result of running the reducer across all elements of the array is a single value. The first time that the callback is run there is no "return value of the previous calculation". If supplied, an initial value may be used in its place. Otherwise array element 0 is used as the initial value and iteration starts from the next element (index 1 instead of index 0). - from site

3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
    
    * With normal Promise .then() syntax (borrowed from source listed on bottom of page.)

        - > ```const superagent = require('superagent')```<br><br>
            ```// callback```<br>
            ```superagent```<br>
            ```.post('/api/pet')```<br>
            ```.send({ name: 'Manny', species: 'cat' })// sends a JSON post body```<br>
            ```.set('X-API-Key', 'foobar')```<br>
            ```.set('accept', 'json')```<br>
            ```.end((err, res) => {```<br>
            ```// Calling the end function will send the request```<br>
            ```});```<br>
            ```// promise with then/catch```<br>
            ```superagent.post('/api/pet').then(console.log).catch(console.error)```;<br>

    * Again with async / await syntax (borrowed from source listed on bottom of page.)

        - >```const superagent = require('superagent');```<br><br>
            ```// callback```<br>
            ```superagent```<br>
            ```.post('/api/pet')```<br>
            ```.send({ name: 'Manny', species: 'cat' })// sends a JSON post body```<br>
            ```.set('X-API-Key', 'foobar')```<br>
            ```.set('accept', 'json')```<br>
            ```.end((err, res) => {```<br>
            ```// Calling the end function will send the request```<br>
            ```});```<br>
            ```// promise with async/await```<br>
            ```(async () => {```<br>
            ```try {```<br>
            ```const res = await superagent.post('/api/pet');``` <br>
            ```console.log(res);```<br>
            ```} catch (err) {```<br>
            ```console.error(err);```<br>
            ```}```<br>
            ```})();```<br>

## Things I want to know more about

"Array.prototype.map()" MDN Web Docs, <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map>

"Array.prototype.reduce()" MDN Web Docs, <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce>

"SuperAgent" VisionMedia, <https://visionmedia.github.io/superagent/>

"NPM JS" npmjs, <https://www.npmjs.com/package/superagent>


All definitions and information came from above-listed publication(s).

[<===Back>](README.md)
