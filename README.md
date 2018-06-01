# week0.day1.arrays

## Array basics

### 1. Mastering syntax
- Create a file called `basics.js`. 
- In this file, define an array called `list` that contains the values: 3, 1, 5, 29, -17
- Print out the 2nd and 4th elements in `list`
- Execute your JavaScript code using `node basics.js` on the command line to see whether everything works.

### 2. Printing an array
Given the following array:

```
const list = [10, 20, 30, 40, 50, 60, 70];
```

Write code that prints out each element of the array on a separate line.

### 3. Modifying an array

Given the following array:

```
const list = [1, 2, 3, 4, 5];
```

Write code that multiplies each element of the array by 2. After you're done, print out each value of the array to make sure that you've done this correctly.

## Array transformations

Write code to transform the given array into the "after" state.
- Do not reassign the entire array (you can't since it is declared `const`).
- Do not use loops yet (we will practice this later)

EXAMPLE: Transform `list` into the "after" state:

```
const list = [1, 2, 3, 4]; 
//    AFTER: [0, 0, 0, 0]
```

One solution:

```
list[0] = 0;
list[1] = 0;
list[2] = 0;
list[3] = 0;
```

### 1. Transform `list` into the "after" state, using the [`push`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push) method.

```
const list = [1, 2, 3, 4]; 
//    AFTER: [1, 2, 3, 4, 5]
```


### 2. Transform `list` into the "after" state, using the [`pop`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop) method.

```
const list = [1, 2, 3, 4, 5]; 
//    AFTER: [1, 2, 3]
```


## Array mysteries

### 

### 99. Look over this worksheet to help fill in any gaps. We’ll be reviewing these on Monday!
- *NOTE: this is NOT homework. From the past two years, students have REQUESTED worksheets, so I have provided them. Use them at your discretion!*
   - [Worksheet: Arrays](https://docs.google.com/document/d/182XxytSNzySXnKOS0bmMDGMHqDvPqcwLKJNTbr74s1Y/edit?usp=sharing)
     - [Worksheet: Arrays (Answers)](https://docs.google.com/document/d/1VfKA18Cs2QO5mUZY4WNlD4_q6sf1KYq9ZxNvyvsi3nQ/edit?usp=sharing)

## Spot the bug

### Syntax errors
