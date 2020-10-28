# Functional Programming


## functional programmin means : "— a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data —"

#### pure function : the function considered as a pure function if it returns a result that similar to the given arguments, also it is not causing any side effects.

#### to make the function a pure functtion you need to give it the argument that it needs in the line codes .. 

    let c=3;
    function power(e) {
        return pow(e,c)
    }
    power(2); // this is not a pure function 

    let c=3;
    function power(e,c) {
        return pow(e,c)
    }
    power(2,c); // this is a pure function 

#### the function that relies on a random number generator cannot be pure.

#### observable side effects means that there is a a global object or a parameter passed by reference.

### benefits:

* The code easier to test.

### to handle the immutability:

* toLowerCase: converts the string to all lower case
* trim: removes whitespace from both ends of a string
* split and join: replaces all instances of match with replacement in a given string

#### "pure functions + immutable data = referential transparency".

#### Filter: filter function return a true or false value.

#### Map: map transform a given array into a new array.

#### Reduce: receive a function and a collection, and return a value created by combining the items.


