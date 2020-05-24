## Imp Notes:

interface --> interfaces are used to define objects in TypeScript
Typed Arguments --> TypeScript allow to declare DataTypes for Function arguments, so its easy to catch type mismatch when a function is called.

========================================================================================================================================================================
Refactored logging to a separate method that accepts 'Typed Arguments'
========================================================================================================================================================================
**_index.js_**

1. logTodo --> added a new function that accepts 'Typed Arguments'
2. moved 'console.log' part to 'logTodo' function.

========================================================================================================================================================================
Used 'interface' to define a Todo object
========================================================================================================================================================================
**_index.js_**

1. interface Todo --> added this interface to define a Todo object
2. fretching 'response.data' as a Todo object'
3. extracted Todo items (Todo object help corectly fetch the items from JSON response) and assignerd them to different vraibles.
4. console.log --> Individually printed each fetched item in 'console.log'
