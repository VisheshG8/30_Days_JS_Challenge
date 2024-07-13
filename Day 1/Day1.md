### Day 1: Variables and Data Types Report Card

**Activities Completed:**
1. **Variable Declaration:**
   - Declared a variable using `var` and assigned a number.
   - Declared a variable using `let` and assigned a string.

2. **Constant Declaration:**
   - Declared a variable using `const` and assigned a boolean.

3. **Data Types:**
   - Created variables of different data types (number, string, boolean, object, array) and logged their types using `typeof`.

4. **Reassigning Variables:**
   - Declared a variable using `let`, assigned an initial value, reassigned a new value, and logged both values.

5. **Understanding `const`:**
   - Attempted to reassign a variable declared with `const` and observed the error.

**Code Summary:**
```javascript
// Activity 1: Variable Declaration
var number = 2;
console.log(number); // 2

let word = 'Vishesh';
console.log(word); // Vishesh

// Activity 2: Constant Declaration
const result = true;
console.log(result); // true

// Activity 3: Data Types
let num = 2;
let str = 'Vishesh';
let bool = true;
let obj = { 
    name: 'Vishesh',
    result: true,
    marks: 10
};
let arr = [10, 20, 'marks', true];

console.log(typeof(num));       // number
console.log(typeof(str));       // string
console.log(typeof(bool));      // boolean
console.log(typeof(obj));       // object
console.log(typeof(arr));       // object

// Activity 4: Reassigning Variables
let newWord = 'oldWord';
console.log(newWord); // oldWord
newWord = 'newWord';
console.log(newWord); // newWord

// Activity 5: Understanding const
const initialWord = 'initialValue';
initialWord = 'newValue'; // TypeError: Assignment to constant variable.
```

**Achievements:**
- Learned how to declare variables using `var`, `let`, and `const`.
- Understood the different data types in JavaScript.
- Used the `typeof` operator to identify the data type of a variable.
- Understood the concept of variable reassignment and the immutability of `const` variables.