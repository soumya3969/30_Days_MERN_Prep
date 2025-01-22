### Variables

Variables in JavaScript are used to store data values that can be referenced and manipulated in your program.

- **Declaring Variables**: JavaScript uses `var`, `let`, and `const` to declare variables.

  - `var`: Older way to declare variables. It is function-scoped.
    ```javascript
    var name = 'John';
    ```

  - `let`: Introduced in ES6 (ECMAScript 2015), it is block-scoped.
    ```javascript
    let age = 25;
    ```
    - : `Let` can be declaired without initialization, can be assign later.
    - : initial value of `let` will be `uninitialized || undefined`

  - `const`: Also block-scoped and used for constants. Once assigned, its value cannot be changed.
    ```javascript
    const PI = 3.14;
    ```
    - : `const` can't be declaired without initialization, value should be assign at the same time.


### Data Types

JavaScript is dynamically typed, meaning a variable can hold different data types. Major data types include:

- **Primitive Types**:
  
  - `Number`: Represents both integer and floating-point numbers.
    ```javascript
    let count = 10;
    let price = 99.99;
    ```

  - `String`: A series of characters, enclosed in single or double quotes.
    ```javascript
    let greeting = "Hello, world!";
    ```

  - `Boolean`: Represents logical values – `true` or `false`.
    ```javascript
    let isActive = true;
    ```

  - `Undefined`: Indicates a variable that has been declared but not assigned a value.
    ```javascript
    let x;
    console.log(x); // undefined
    ```

  - `Null`: Represents the intentional absence of any object value.
    ```javascript
    let emptyValue = null;
    ```

  - `Symbol`: Introduced in ES6, it is used to create unique identifiers.
    ```javascript
    let sym = Symbol('description');
    ```

- **Non-primitive (Reference) Types**:

  - `Object`: An unordered collection of key-value pairs.
    ```javascript
    let person = { name: "Alice", age: 30 };
    ```

  - `Array`: A special type of object for storing ordered collections.
    ```javascript
    let colors = ["red", "green", "blue"];
    ```

### Operators

Operators in JavaScript are used to perform operations on values and variables. Here’s a quick overview:

- **Arithmetic Operators**: Used to perform mathematical calculations.
  - `+` Addition
    ```javascript
    let sum = 10 + 5; // 15
    ```

  - `-` Subtraction
    ```javascript
    let difference = 10 - 5; // 5
    ```

  - `*` Multiplication
    ```javascript
    let product = 10 * 5; // 50
    ```

  - `/` Division
    ```javascript
    let quotient = 10 / 2; // 5
    ```

  - `%` Modulus (Remainder)
    ```javascript
    let remainder = 10 % 3; // 1
    ```

- **Assignment Operators**: Assign values to variables.
  - `=` Basic assignment
    ```javascript
    let x = 5;
    ```

  - `+=` Add and assign
    ```javascript
    x += 3; // x = x + 3
    ```

  - `-=` Subtract and assign
    ```javascript
    x -= 2; // x = x - 2
    ```

- **Comparison Operators**: Compare values and return a Boolean.
  - `==` Equals (checks value equality)
    ```javascript
    console.log(5 == '5'); // true
    ```

  - `===` Strict equals (checks value and type equality)
    ```javascript
    console.log(5 === '5'); // false
    ```

  - `!=` Not equals
    ```javascript
    console.log(5 != '5'); // false
    ```

  - `!==` Strict not equals
    ```javascript
    console.log(5 !== '5'); // true
    ```

- **Logical Operators**: Combine or invert Boolean values.
  - `&&` Logical AND
    ```javascript
    console.log(true && false); // false
    ```

  - `||` Logical OR
    ```javascript
    console.log(true || false); // true
    ```

  - `!` Logical NOT
    ```javascript
    console.log(!true); // false
    ```

These are the fundamental concepts you'd start with. 

