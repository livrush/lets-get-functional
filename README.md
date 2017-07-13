# lets-get-functional

An exercise in problem solving in the functional idiom.

## Setup

0. If you haven't release your lodown library to `npm` (node package manager), follow the steps in this video to do so:

    [publishing-npm-packages](https://docs.npmjs.com/getting-started/publishing-npm-packages)

1. **FORK** this repository on GitHub to your own GitHub account.

2. From your FORK, use SSH to clone the repository into a Blank Cloud9 workspace.

3. Once the Cloud9 workspace is finished initializing, from the bash terminal, run the command:

    npm install

4. Install your lodown library by running the command and replacing `<my-user-name>` :

    npm install --save lodown-`<my-user-name>` --prefix projects/lets-get-functional

So, if your username was `phrush`, your command would look like this:

    npm install --save `lodown-phrush` --prefix projects/lets-get-functional    

5. Open up `index.js` and import your lodown library using the node `require()` method.

    `const _ = require('<my-user-name>');`

6. Each time you want to test your code, run the following code and run the `index.html` file

    npm run build --prefix projects/lets-get-functional

## Solve

1. Code and test your solutions in `index.js`

    Customer data is available to you in the Array, `customers`
    Utilizing your `lodown` library and the `customers` Array, write the functions outlined below
    In the node.js environment you can both `console.log()` OR use the debugger to step through your code and inspect your work
    Test your code by running `npm start --prefix projects/lets-get-functional` in the terminal, or clicking the `run` button

### 1: `maleCount`
- Objective: Find the number of male customers
- Input: `Array`
- Output: `Number`
- Constraints: use `filter`

### 2: `femaleCount`
- Objective: Find the number of female customers
- Input: `Array`
- Output: `Number`
- Constraints: use `reduce`

### 3: `oldestCustomer`
- Objective: Find the oldest customer's name
- Input: `Array`
- Output: `String`
- Constraints:

### 4: `youngestCustomer`
- Objective: Find the youngest customer's name
- Input: `Array`
- Output: `String`
- Constraints:

### 5: `averageBalance`
- Objective: Find the average balance of all customers
- Input: `Array`
- Output: `Number`
- Constraints:

### 6: `firstLetterCount`
- Objective: Find how many customer's names begin with a given letter
- Input: `Array`, `Letter`
- Output: `Number`
- Constraints:

### 7: `friendFirstLetterCount`
- Objective: Find how many friends of a given customer have names that start with a given letter
- Input: `Array`, `Customer`, `Letter`
- Output: `Number`
- Constraints:

### 8: `friendsCount`
- Objective: Find the customers' names that have a given customer's name in their friends list
- Input: `Array`, `Name`
- Output: `Array`
- Constraints:

### 9: `topThreeTags`
- Objective: Find the three most common tags among all customers' associated tags
- Input: `Array`
- Output: `Array`
- Constraints:

### 10: `genderCount`
- Objective: Create a summary of genders, the output should be:
```javascript
{
    male: 3,
    female: 4,
    transgender: 1
}
```
- Input: `Array`
- Output: `Object`
- Constraints: Use `reduce`
