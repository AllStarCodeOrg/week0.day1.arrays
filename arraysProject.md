# week0.day1.arrays

## Array basics

### 1. Mastering syntax
- If you haven't already done so, create a file called `arrays.js`
- In this file, define an array called `grades` that contains the values: 93, 100, 65, 84, 80
- Print out the 2nd and 4th elements in `grades` (Remember, an item's index is not the same as it's position)
- Execute your JavaScript code using `node arrays.js` on the command line to see that everything is working correctly
- Use this file to test your answers the following questions
   - If you want to remove code, try commenting it out instead
   ```javascript
   // double backslash removes code from execution, but keeps it in the document!
   ```
### 2. Printing an array
Given the following array:

```javascript
const coins = [1, 5, 10, 25, 50];
```

Write code that prints out each element of the array on a separate line (do not use a loop, we'll get there soon!).

### 3. Modifying an array

Given the following array:

```javascript
const lunchSpecials = [5, 10, 6, 7];
```

Write code that reassigns each item to itself multiplied by 2. After you're done, print out each value of the array to make sure that you've done this correctly.

## Array transformations

Write code to transform the given array into the "AFTER" state (see example below)
- Do not reassign the entire array (you can't since it is declared `const`).
- Do not use loops

FOR EXAMPLE: Transform `list` into the "AFTER" state:

```javascript
const list = [1, 2, 3, 4]; 
//    AFTER: [0, 0, 0, 0]
```

One solution:

```javascript
list[0] = 0;
list[1] = 0;
list[2] = 0;
list[3] = 0;
```

### 1. Transform using the [`push`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push) method.

```javascript
const list = [1, 2, 3, 4]; 
//    AFTER: [1, 2, 3, 4, 5]
```


### 2. Transform using the [`pop`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop) method.

```javascript
const list = [1, 2, 3, 4, 5]; 
//    AFTER: [1, 2, 3]
```

### 3. Transform using the [`unshift`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift) method.

```javascript
const list = [1, 2, 3, 4, 5]; 
//    AFTER: [7, 6, 1, 2, 3, 4, 5];
```
### 4. Transform using the [`reverse`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse) method.

```javascript
const list = [1, 2, 3, 4, 5]; 
//    AFTER: [5, 4, 3, 2, 1];
```
### 5. Transform using the [`splice`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) method.

```javascript
const list = [1, 2, 3, 4, 5]; 
//    AFTER: [1, 2, 3, 99, 5];
```

## Array Info
```javascript
let items = ["Boots of Speed", "Health Potion", "Doran's Blade", "Warding Totem"];
```
### Using the above array, gather the following information without using __inefficient human tactics__. Why? This array changes often! Items are taken away and added, so your code must be able to handle that - see the link for help:
1. What is the length of the array? 
   - See [.length](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/length)
2. Is there a "Boots of Speed" in the array?
   - See [.includes()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)
3. Is there a "Lich Bane" in the array?
4. What's the index of the "Health Potion" in the array?
   - See [.indexOf()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf)

## Array Info (20 minutes later)
```javascript
console.log(items);
// ["Ionian Boots of Lucidity", "Infinity Edge", "Lich Bane", "Luden's Echo","Spirit Visage"];
```
### Go figure, the array has changed! The code you made from before should still answer the above questions correctly without any changes!

1. Make sure the code from before works correctly with this new array
2. Don't ask what kind of build this is, because I don't know

## Spot the error
### Pretend to be the computer for a moment and find what the error is before running it. Note: some things may be of poor design, but not technically cause an error

1. ```javascript
    cosnt myArray = [2,4,5,7];
    ```

2. ```javascript
    const myArray = [
      "this",
      "is",
      "correct",
    ]
    ```

3. ```javascript
    const list = [1,3,4,5,7,8];
    list[1] = 5;
    list = list.reverse();
    ```

4. ```javascript
    const "myList" = ["something","more"];
    ```

5. ```javascript
    let tic_tac_toe = [
      [O,O,X],
      [O,X,X],
      [O,X,O]
    ];
   ```

## Modification through `.length`
```javascript
const x = [4,5,6,7,4,1,1];
x.length; // 7
x.length = 3;
x.length; // 3
console.log(x);
```
### Try this out. What happened to the array?

## Look over this worksheet to help fill in any gaps. We’ll be reviewing these on Monday!
- *NOTE: this is NOT homework. From the past two years, students have REQUESTED worksheets, so I have provided them. Use them at your discretion!*
   - [Worksheet: Arrays](https://docs.google.com/document/d/182XxytSNzySXnKOS0bmMDGMHqDvPqcwLKJNTbr74s1Y/edit?usp=sharing)
     - [Worksheet: Arrays (Answers)](https://docs.google.com/document/d/1VfKA18Cs2QO5mUZY4WNlD4_q6sf1KYq9ZxNvyvsi3nQ/edit?usp=sharing)

