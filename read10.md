# call stack 

### 'it is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function'.


#### The understanding of the call stack is vital to Asynchronous programming (which we will look at in a later article.

#### call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

#### Temporarily store: This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.

### debugging 

#### Syntax errors : example

    JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1

#### Range errors : example

    var foo= []
    foo.length = foo.length -1 // Uncaught RangeError: Invalid array length

#### Call stack : testing is automatically called since it’s an IIFE (immediately Invoked Function Expression);
#### the function add is called again, this time with number, the values are added making it 3 but then, split (which is not available for number type variables) is called which makes an error being thrown.

#### Handling errors : using try…catch when the type checks are becoming "longer than your function logic".