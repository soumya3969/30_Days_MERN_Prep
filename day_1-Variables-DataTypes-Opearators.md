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

