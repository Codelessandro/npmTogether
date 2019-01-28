# npmTogether
## Steps
1. Create your own npm package. It should export a function that takes two arguments: 
a number and a callback function. Do a calculation inside setTimeout and after the calculation 
call the callback function passing null as error and the result of your calculation as success parameter.
2. In your (c9) machine type: "npm login" (Username: webtechtut // PW: [mentionied in Tutorium] // Email: alessandro.schneider@campus.tu-berlin.de)
3. Type "npm whoami" to see if you are logged in
4. Type: "npm publish --access public"
5. Take a coffee ☕
6. Create a new npm package.
7. Install your previous uploaded package as a dependency and also your neighbours package.
8. Call one of the two functions and inside the callback call the second one. The inner callback should console log the final result (your number put inside the composition of the two functions).
9. Take a coffee ☕
10. Advanced if time left over:
10. Add to your module.exports another implementation of your func using Promises
11. update your package with a new package version number
12. Refactor your code: use promises instead of callbacks (if your neighbour did not offer a promisified version have a look at: https://www.npmjs.com/package/es6-promisify)
13. Take a big coffee ☕


