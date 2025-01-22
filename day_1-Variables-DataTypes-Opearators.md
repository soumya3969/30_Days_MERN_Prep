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
